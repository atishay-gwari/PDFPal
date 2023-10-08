# Langchain-PDFPal

Welcome to PDFPal, your personal document assistant! This project is the first implementation of Langchain, a powerful natural language processing and chatbot framework. PDFPal allows users to interact with and extract information from PDF documents using a conversational interface powered by Langchain.

## Overview

PDFPal is a web application that leverages Langchain's to assist users in processing PDF documents. It combines text extraction, text chunking, and natural language understanding to enable users to ask questions about their documents and receive informative responses.

## Features

- **Text Extraction**: PDFPal extracts text content from uploaded PDF documents, making it accessible for further processing.

- **Text Chunking**: To enhance efficiency, the extracted text is divided into smaller chunks, enabling the chatbot to manage and retrieve relevant information effectively.

- **Conversational Interface**: Users can ask questions about their documents using a chatbot-like interface, and PDFPal provides responses based on Langchain's natural language processing.

- **OpenAI Integration**: PDFPal utilizes the OpenAI API to generate responses, making it capable of understanding and responding to user queries effectively.

## Getting Started

### Prerequisites

Before you can run PDFPal, ensure you have the following prerequisites:

- [Python](https://www.python.org/) (Version 3.9)
- An OpenAI API key (Get one from the [OpenAI website](https://beta.openai.com/signup/))

### Installation

1. Clone this repository to your local machine:

   ```shell
   git clone https://github.com/yourusername/langchain-pdfpal.git
   ```

2. Install the required Python packages using pip:
    ```shell
    pip install -r requirements.txt

    ```
3. Start the PDFPal web application
    ```shell
    streamlit run app.py

    ```
    

