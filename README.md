# 📄 AI Resume Analyzer

An AI-powered Resume Analyzer built using **Python**, **Machine Learning**, **Natural Language Processing (NLP)**, and **Gradio**. The application analyzes resumes in PDF format, predicts the most suitable job role, detects technical skills, calculates a resume score, identifies missing skills, and provides personalized improvement suggestions.

---

## 📌 Project Overview

The AI Resume Analyzer automates the resume evaluation process using Machine Learning and Natural Language Processing techniques. It extracts text from uploaded PDF resumes, preprocesses the content, predicts the candidate's job role using a trained Logistic Regression model, identifies technical skills, calculates a resume score based on role-specific requirements, and generates personalized suggestions for improvement.

The application provides an easy-to-use Gradio interface, allowing users to upload a resume and receive instant AI-powered analysis.

---

## ✨ Features

- 📄 Upload resumes in PDF format
- 🤖 Predicts the candidate's job role
- 🧠 NLP-based resume preprocessing
- 🔍 Detects technical skills automatically
- 📊 Calculates a resume score
- ⚠️ Identifies missing role-specific skills
- 💡 Generates personalized improvement suggestions
- 🌐 Interactive Gradio web interface

---

## 🛠️ Technologies Used

- Python
- Google Colab
- Pandas
- NLTK
- TF-IDF Vectorizer
- Scikit-learn
- Logistic Regression
- PDFPlumber
- Gradio

---

## 📂 Dataset

This project was trained using the **Updated Resume Dataset**.

Download the dataset and update the dataset path in the notebook before retraining the model.

**Note:** The trained model (`resume_model.pkl`) and TF-IDF vectorizer (`tfidf_vectorizer.pkl`) are included in this repository, so retraining is not required for resume analysis.

---

## ⚙️ Machine Learning Workflow

1. Load and preprocess the resume dataset.
2. Convert resume text into numerical features using TF-IDF.
3. Train a Logistic Regression classifier.
4. Save the trained model and vectorizer.
5. Extract text from uploaded PDF resumes.
6. Predict the candidate's job role.
7. Detect technical skills.
8. Calculate the resume score.
9. Identify missing skills.
10. Generate personalized suggestions.

---

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/mikeyscript/AI-Resume-Analyzer.git
```

### 2. Install the required libraries

```bash
pip install pandas nltk scikit-learn pdfplumber gradio
```

### 3. Download the required NLTK data

```python
import nltk
nltk.download("stopwords")
```

### 4. Run the notebook

Open and execute the notebook in Google Colab.

---

## 🚀 Usage

- Upload a resume in PDF format.
- The application extracts the resume text.
- The trained model predicts the candidate's job role.
- Technical skills are detected automatically.
- A resume score is calculated.
- Missing skills and personalized suggestions are displayed.

---

## 📁 Project Structure

```
AI-Resume-Analyzer/
│
├── AI_Resume_Analyzer.ipynb
├── resume_model.pkl
├── tfidf_vectorizer.pkl
├── README.md
├── .gitignore
└── LICENSE
```

---

## 🔮 Future Improvements

- Support for DOCX resumes
- Named Entity Recognition (NER) for better skill extraction
- ATS compatibility analysis
- Resume ranking system
- Improved recommendation engine
- Flask or Streamlit web application

---

## 👨‍💻 Author

**Prajeesh**

Machine Learning & Artificial Intelligence Enthusiast

---

## 📜 License

This project is licensed under the MIT License.
