# Please run the Gradio again for the results , the genrated link expires within 72 hours


# PDF Question Answering Bot

## Overview

The PDF Question Answering Bot is a tool designed to extract text from PDF documents and answer user queries based on the content of those documents. This application integrates several components including text extraction, embedding generation, vector storage, and natural language response generation.

## Components

- **Text Extraction**: Extracts text from PDF files using PyPDF2.
- **Text Chunking**: Divides the extracted text into manageable chunks for processing.
- **Embedding Generation**: Converts text chunks into embeddings using Sentence Transformers.
- **Vector Storage**: Stores and manages embeddings using Pinecone.
- **Response Generation**: Generates answers based on user queries using Cohere.

## Setup

1. **Install Dependencies**:
   ```bash
   pip install gradio sentence-transformers pinecone-client cohere PyPDF2
