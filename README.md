# Resume-Screening-Using-NLP

This project uses NLP to match candidate resumes with job descriptions and rank them based on relevance.

## 🔧 Technologies Used
- Python
- spaCy
- scikit-learn
- Streamlit

## 🚀 Features
- Upload a CSV of resumes
- Paste any job description
- See top matches with similarity scores
- Download the ranked result

## 📁 Dataset Format
CSV should contain at least:
- `Resume_str` — Raw resume text
- `ID`, `Category` (optional for display)

## ▶️ How to Run Locally

```bash
pip install -r requirements.txt
python -m spacy download en_core_web_sm
streamlit run app.py
