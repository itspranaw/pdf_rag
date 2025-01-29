# Chat with PDF App

A Streamlit-based application that enables interaction with PDF documents using Large Language Models (LLMs). This tool allows users to upload PDFs, ask questions, and extract information from them through a conversational interface.

## Features

- Upload and parse PDF documents.
- Ask questions or search for specific information within the PDF.
- Receive responses generated by a language model based on the content of the document.
- Simple, user-friendly interface using Streamlit.

## Requirements

- Python 3.9+
- Ollama (running locally)
  - Deepseek R1 minimum (RTX 3060 8 GB VRAM required for the deepseek r1 model)
  
## Installation

1. **Clone this repository:**
   ```bash
   git clone <repository-url>
   cd <repository-directory>
2. **Set up a virtual environment:**

***For Linux/Mac:***
```bash
python -m venv venv
source venv/bin/activate
```
***For Windows:***
```bash
python -m venv venv
venv\Scripts\activate
```

3. **Install dependencies:**

```bash
pip install -r requirements.txt
```
4. **Install and configure Ollama:**

Install Ollama by following the official installation guide.
Pull the required model:
```bash
ollama pull <model>
```
5. **Start the Streamlit app:**

```bash
streamlit run pdf_rag.py
```
