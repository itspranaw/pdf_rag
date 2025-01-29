# Chat with PDF App

A Streamlit application for interacting with PDF documents using LLMs.

## Requirements

- Python 3.9+
- Ollama running locally (For deepseek r1 minimum RTX 3060 8 GB VRAM)
- Pull the model before using ``` ollama pull <model>

## Installation
```bash
python -m venv venv
source venv/bin/activate  # Linux/Mac
# or venv\Scripts\activate  # Windows
pip install -r requirements.txt