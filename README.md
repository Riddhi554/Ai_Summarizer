# PDF Text Summarizer

This repository contains a script that extracts text from a PDF file and summarizes it using Hugging Face transformers. The interface is built using Gradio, allowing for easy interaction through a web-based interface.

## Features

- Extracts text from PDF files using PyMuPDF (fitz).
- Summarizes extracted text using the Hugging Face `facebook/bart-large-cnn` model.
- Provides a simple web interface using Gradio for uploading PDF files and viewing summaries.

## Installation

To run the script, you need to install the following Python packages:

- `transformers`
- `pymupdf`
- `gradio`

You can install these packages using pip:

```bash
pip install transformers pymupdf gradio
