# PDF-AI-Assisstant
The PDF AI Assistant is a Flask-based web application designed to provide instant, context-aware answers from uploaded PDF documents, leveraging advanced natural language processing to extract and analyze text, offering precise references to specific locations within the documents for efficient information retrieval.

## Overview
`PDF AI Assistant` is a web application that helps users extract and analyze information from PDF documents. Using advanced natural language processing, this tool provides context-aware answers that reference specific document locations, facilitating efficient information retrieval.

## Features
- Upload PDF files for analysis.
- Extract text and metadata from PDFs.
- Search through content using NLP models for specific information.
- Interactive chat interface for querying document content.
- References provided for answers indicating PDF, page, and line.

## Technologies Used
- Flask
- PyPDF2
- Sentence Transformers
- Google's Gemini API

## Setup and Installation
1. Ensure you have Python installed on your machine.
2. Install necessary Python packages:
   ```bash
   pip install flask requests PyPDF2 sentence-transformers

## Clone the repository:
git clone <repository-url>
cd PDF-AI-Assistant

## Run the application:
python app.py

## Usage:
Navigate to http://localhost:5000/ on your web browser.
Use the interface to upload PDF files and enter queries to receive answers based on the content.

## Contributing:
Contributions are welcome! For major changes, please open an issue first to discuss what you would like to change.
