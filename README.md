MSc Dissertation Project – Bournemouth University
# Automated Essay Grading System using LLMs


This project implements an **Automated Essay Scoring System** using a fine-tuned transformer model.  
The application allows users to upload essays and receive an automatically predicted score along with feedback.

The system uses **Natural Language Processing (NLP)** techniques and a transformer model to evaluate written essays and simulate automated grading.

---

## Features

- Upload essays in **TXT, PDF, or DOCX** format
- Automatic **essay scoring using a transformer model**
- **NLP preprocessing pipeline**
- **Automated feedback generation**
- Simple **web interface using Flask**

---

## Tech Stack

- Python
- Flask
- PyTorch
- HuggingFace Transformers
- PyPDF2
- python-docx
- HTML / CSS

---

## Project Structure
automated-essay-grading-llm
│
├── app.py
├── requirements.txt
├── style.css
├── video_automated_essay_grading.mp4
├── README.md
└── docs
    └── dissertation.pdf





---

## How the System Works

1. User uploads an essay file (TXT, PDF, DOCX) or enters text manually.
2. Text is extracted from the file.
3. The essay is processed using a **transformer tokenizer**.
4. The fine-tuned model predicts a **score**.
5. The system generates **feedback based on the score**.

---

Clone the repository

git clone https://github.com/yourusername/automated-essay-grading-llm.git

Install dependencies

pip install -r requirements.txt

Run the application

python app.py
---

## Research Background

This project was developed as part of an **MSc Data Science & Artificial Intelligence dissertation**.  
It explores the use of **Large Language Models (LLMs)** for automated essay grading.

---

## Future Improvements

- Improve scoring accuracy with larger datasets
- Deploy the application using **Docker / cloud platforms**
- Build a more advanced **frontend interface**
- Add grammar and coherence analysis

---

## Author

**Pavan Raghavendra Sai Chintala**

MSc Data Science & Artificial Intelligence  
Bournemouth University  
