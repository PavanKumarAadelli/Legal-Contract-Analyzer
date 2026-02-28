# 📜 The Fine Print Guardian - Legal Contract Risk Analyzer

## 🚀 About The Project
This is an AI-powered tool built to assist non-lawyers in understanding legal documents. It uses Natural Language Processing (NLP) to scan PDF contracts and highlight potentially dangerous clauses (like hidden penalties or termination triggers) instantly.

## 🛠️ Tech Stack
*   **Python**: Core Logic
*   **SpaCy (NLP)**: For Named Entity Recognition and Sentence Segmentation
*   **Streamlit**: For the interactive Web UI
*   **pdfplumber**: For extracting text from PDFs

## 🔍 How It Works
1.  User uploads a legal PDF (Rental Agreement, Employment Contract, etc.).
2.  The system extracts text and breaks it into sentences.
3.  A custom NLP pipeline scans for a predefined list of "Risk Keywords" (e.g., "indemnify", "breach", "penalty").
4.  It outputs a side-by-side comparison: **Risky Clauses** vs **Key Details (Dates/Money)**.

## 💡 Why This Project?
Most people sign contracts without reading them. This tool acts as a "first line of defense," bringing transparency to complex legal text in seconds.

## 📸 Demo
<img width="1852" height="728" alt="Image" src="https://github.com/user-attachments/assets/8addd72e-76f3-4cf2-8f46-40cdf4e352d3" />

## ⚙️ Run Locally
1.  Install requirements: `pip install streamlit spacy pdfplumber`
2.  Download model: `python -m spacy download en_core_web_sm`
3.  Run the app: `streamlit run app.py`
