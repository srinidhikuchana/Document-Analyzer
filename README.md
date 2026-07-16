# Document Analyzer

A Gradio application powered by Google Gemini that analyzes PDF and image documents.

## Features

-  Extract text from uploaded documents
-  Generate concise summaries
-  Ask questions about the document
-  Convert summaries to speech using gTTS

## Installation

```bash
pip install -r requirements.txt
```

Set your Gemini API key:

**Windows**

```cmd
set GEMINI_API_KEY=YOUR_API_KEY
```

**Linux/macOS**

```bash
export GEMINI_API_KEY=YOUR_API_KEY
```

Run the application:

```bash
python app.py
```

## Technologies Used

- Python
- Gradio
- Google Gemini API
- gTTS

## Project Structure

```
.
├── app.py
├── requirements.txt
└── README.md
```
