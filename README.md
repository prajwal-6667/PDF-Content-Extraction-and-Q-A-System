# PDF-Content-Extraction-and-Q-A-System
This project is a PDF content extraction and question-answering system that leverages Google Generative AI models to process and answer questions based on the content of PDF documents. The system is built using a combination of Google Colab, Flask, and various Python libraries.

Overview
This project is a PDF content extraction and question-answering system that leverages Google Generative AI models to process and answer questions based on the content of PDF documents. The system is built using a combination of Google Colab, Flask, and various Python libraries.

Key Features:
Extracts and processes text from PDF documents.
Splits text into manageable chunks for efficient processing.
Uses generative AI models to create embeddings and answer questions.
Provides a web interface for users to upload PDFs and query the system.
Installation
Prerequisites
Ensure you have Python 3.x installed. You can download Python from python.org.

Setting Up the Environment
Clone the Repository

bash
Copy code
git clone https://github.com/your-username/pdf-qna-system.git
cd pdf-qna-system
Create a Virtual Environment

bash
Copy code
python -m venv venv
Activate the Virtual Environment

On Windows:
bash
Copy code
venv\Scripts\activate
On macOS/Linux:
bash
Copy code
source venv/bin/activate
Install Dependencies

bash
Copy code
pip install -r requirements.txt
Requirements File (requirements.txt)
Add the following packages to your requirements.txt:

arduino
Copy code
google-generativeai
langchain-google-genai
chromadb
pypdf
langchain
langchain-community
langchain-text-splitters
flask
flask-ngrok
requests
