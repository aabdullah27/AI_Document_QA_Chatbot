# Document QA Bot 📚

## Overview

The **Document QA Bot** is a streamlined question-answering application that allows users to upload PDF, DOCX, or TXT files and ask questions about the document content. Using embeddings and a language model, the bot quickly retrieves relevant information, helping users explore their documents interactively.

Try out the live demo here:  
[![Open in Streamlit](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://ai-doc-chatbot.streamlit.app/)

## Features

- **File Upload**: Supports PDF, DOCX, and TXT file formats for document submission.
- **Question Answering**: Provides answers to user questions based on the uploaded document content.
- **Multi-Document Processing**: Processes multiple documents at once and retrieves information from any of them.
- **Interactive Chat Interface**: Built with Streamlit for a smooth, responsive experience.
- **Embedding and LLM Integration**: Leverages Hugging Face embeddings and the Groq language model for high-quality text understanding and response generation.
- **Clear Chat History Option**: Users can reset the chat interface to start fresh with new queries.

## Technologies Used ⚙️

- **Python**: The main programming language for development.
- **Streamlit**: Framework for creating the interactive web interface.
- **Hugging Face Transformers**: For generating embeddings to process and understand document content.
- **FAISS**: Used for efficient vector similarity search.
- **Groq Language Model**: Enhances the Q&A experience by delivering precise answers.

## Installation ⏳

To set up and run the Document QA Bot locally, follow these steps:

### Clone the Repository
```bash
git clone https://github.com/yourusername/document-qa-bot.git
cd document-qa-bot
