OCR-Summarization-QnA

🚀 Automated Text Extraction, Summarization, and QnA using OCR & AI

📌 Project Overview

This project automates text extraction from PDFs and images (JPG, PNG, etc.), processes the text using Natural Language Processing (NLP), generates summarized content, and allows interactive Q&A using OpenAI GPT-4o.
✨ Features

✅ OCR (Optical Character Recognition) to extract text from images & scanned PDFs
✅ Text Summarization using TextRank & NLP
✅ Question Answering (QnA) using BERT and OpenAI GPT-4o
✅ Multi-format support (PDF, JPG, PNG)
✅ Flexible AI model selection (Local BERT vs. GPT-4o for QnA)

📂 OCR-Summarization-QnA
│── 📂 src/                  # Main source code
│   ├── main.py              # Main script to run extraction & QnA
│   ├── ocr.py               # Module for reading text from images/PDF
│   ├── summarization.py     # Module for text summarization
│   ├── qna.py               # Module for QnA (BERT & GPT-4o)
│   ├── config.py            # API Key & settings configuration
│── 📂 data/                 # Example files (PDF, images)
│── 📂 docs/                 # Documentation files
│── README.md                # Project documentation
│── requirements.txt         # Dependencies list
│── .gitignore               # Files to ignore in Git
│── LICENSE                  # Project license
