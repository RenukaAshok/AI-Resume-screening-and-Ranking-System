# AI-Resume-screening-and-Ranking-System
# 🚀 Resume Ranking System using Streamlit

This project is an AI-based Resume Ranking System built using Python and Streamlit. It helps recruiters and job seekers by ranking resumes based on their similarity to a given job description using **TF-IDF** and **Cosine Similarity** techniques.

---

## ✨ Features

- 📤 Upload multiple PDF resumes.
- 📝 Input custom job descriptions.
- 📊 Automatically rank resumes based on content relevance.
- 💡 AI-powered suggestions to improve resume quality.
- 🎨 Interactive and clean user interface using custom CSS.
- ✅ Visual ranking table with match scores and recommendations.

---

## 🛠️ Technologies Used

- Python 🐍
- Streamlit
- PyPDF2
- Scikit-learn
- Pandas
- Matplotlib (for UI customization)

---

## 🚩 How It Works?

1. Upload one or more resumes in PDF format.
2. Paste or type the job description.
3. Click to process.
4. The system will:
   - Extract text from PDFs.
   - Compute TF-IDF vectors.
   - Calculate Cosine Similarity between job description and resumes.
   - Display ranked results with match scores and AI suggestions.

---

## ✅ Installation

```bash
git clone https://github.com/YourUsername/YourRepositoryName.git
cd YourRepositoryName
pip install -r requirements.txt
streamlit run app.py
