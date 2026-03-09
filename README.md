# Automated Essay Grading System using LLMs

MSc Dissertation Project – Bournemouth University

This project implements an **Automated Essay Scoring System** using a **fine-tuned transformer model (DeBERTa v3)**. The system evaluates essays and predicts a score automatically using Natural Language Processing (NLP) techniques.

The application allows users to upload essays and receive an automatically predicted score along with feedback through a simple web interface.

---

## Features

* Upload essays in **TXT, PDF, or DOCX** format
* Automatic **essay scoring using a fine-tuned transformer model**
* **NLP preprocessing pipeline** for essay text
* **Automated feedback generation** based on predicted score
* Simple **Flask web interface** for interaction

---

## Tech Stack

* Python
* PyTorch
* HuggingFace Transformers
* Flask
* PyPDF2
* python-docx
* HTML / CSS

---

## Model

The essay scoring model is built using a **fine-tuned DeBERTa-v3 transformer** for sequence classification.

The training pipeline includes:

* Text preprocessing and cleaning
* Tokenization using HuggingFace tokenizers
* Fine-tuning a transformer model
* Model evaluation on validation data

---

## Project Structure

```
automated-essay-grading-llm
│
├── app/
│   ├── app.py
│   ├── templates/
│   │   └── index.html
│   └── static/
│       └── style.css
│
├── dataset/
│
├── notebooks/
│
├── preprocessing/
│
├── results/
│
├── docs/
│   └── dissertation.pdf
│
├── demo/
│   └── video_automated_essay_grading.mp4
│
├── README.md
└── requirements.txt
```

---

## How the System Works

1. The user uploads an essay file (**TXT, PDF, or DOCX**) or enters text manually.
2. Text is extracted from the uploaded file.
3. The essay text is processed using an **NLP preprocessing pipeline**.
4. The processed text is tokenized using a **transformer tokenizer**.
5. The fine-tuned model predicts an **essay score**.
6. The system generates **feedback based on the predicted score**.

---

## Installation

Clone the repository

```
git clone https://github.com/yourusername/automated-essay-grading-llm.git
```

Install dependencies

```
pip install -r requirements.txt
```

Run the application

```
python app/app.py
```

---

## Research Background

This project was developed as part of an **MSc Data Science & Artificial Intelligence dissertation at Bournemouth University**.

The research explores how **Large Language Models (LLMs)** can be applied to automate essay grading and assist educational evaluation systems.

---

## Demo

A short demonstration of the automated essay grading system is included in the repository.

Demo video:

```
demo/video_automated_essay_grading.mp4
```

---

## Future Improvements

* Improve scoring accuracy using **larger datasets**
* Deploy the system using **Docker or cloud platforms**
* Build a more advanced **frontend interface**
* Add **grammar, coherence, and readability analysis**

---

## Author

**Pavan Raghavendra Sai Chintala**

MSc Data Science & Artificial Intelligence
Bournemouth University
