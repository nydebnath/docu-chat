# DocuChat: Interact with Your Documents

## Overview
DocuChat is an AI-powered application that lets you upload a document (PDF or text) and interact with it through a chat interface. Using advanced AI capabilities, DocuChat allows you to ask questions about the document and get precise answers, making it easy to explore and understand large texts.

## Features
- Upload `.pdf` or `.txt` documents.
- Chat with your document to extract relevant information.
- Retain context from previous questions for seamless interaction.

## How It Works
1. **Document Upload**:
   - The uploaded document is processed, and its content is indexed for efficient searching.
2. **AI Question-Answering**:
   - A conversational AI system (QA chain) is set up to retrieve and answer questions based on the document content.
3. **Interactive Chat**:
   - Ask questions through a user-friendly interface, and the AI provides contextual and accurate responses.

## Setup Instructions

### Prerequisites
- Python 3.8 or higher
- Install the required libraries:
  ```bash
  pip install langchain langchain-openai gradio
  ```

### Environment Setup
1. Get an OpenAI API key from [OpenAI](https://platform.openai.com/).
2. Set the API key as an environment variable:
   ```bash
   export OPENAI_API_KEY="your-openai-api-key"
   ```

### Run the Application
1. Open the `document_chat.ipynb` file in Jupyter Notebook or JupyterLab.
2. Follow the instructions in the notebook to execute the cells step by step.
3. Open the Gradio interface in your browser (the URL will appear when you run the last cell).

## Usage
1. **Upload a Document**:
   - Click the "Upload Document" button to select a PDF or text file.
2. **Ask Questions**:
   - Type your question in the text box and click "Ask".
3. **View Responses**:
   - The chatbot will display the answer, retaining the context of previous questions.

## Example Use Cases
- Quickly find information in a lengthy research paper or book.
- Interact with meeting notes or documentation for clarity.
- Study or summarize large texts more efficiently.

## File Structure
- `document_chat.ipynb`: Jupyter Notebook containing the application code and instructions.
- `README.md`: Documentation file (this file).

## Limitations
- Only supports `.pdf` and `.txt` files.
- Requires an active internet connection to access OpenAI APIs.

## Contributing
If you'd like to contribute, feel free to fork the repository, make changes, and submit a pull request.

## License
This project is licensed under the MIT License. See `LICENSE` for more details.

