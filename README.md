# 📄 AI Resume Screening System using Machine Learning

## 🚀 Overview
This project is an AI-powered Resume Screening System that uses Natural Language Processing (NLP) and Machine Learning to match resumes with job descriptions and generate a compatibility score.

It helps automate the hiring process by analyzing resumes intelligently instead of manual checking.

---

## 🧠 Features
- 📄 Upload Resume (PDF)
- 📝 Enter Job Description
- 🤖 ML-based Match Prediction
- 📊 Match Score (%)
- 🌐 Language Selection Option
- 🌗 Light / Dark Theme Toggle
- ⚙️ Settings Panel
- 📌 Clean UI Interface

---

## 🛠️ Tech Stack
- Python
- Scikit-learn
- Pandas
- NumPy
- NLTK
- PDFPlumber
- Gradio / Colab UI

---

## ⚙️ How It Works

1. User uploads resume (PDF)
2. User enters job description
3. System extracts text from PDF
4. Text is cleaned using NLP techniques
5. TF-IDF converts text into numerical features
6. Machine Learning model predicts match score
7. Final result is displayed (Strong / Weak Match)

---

## 📊 Output Includes
- Match Score (%)
- Prediction (Strong / Weak Fit)
- Resume Preview
- Skill Matching Analysis

---

# 📸 Project Screenshots

## 🟢 1. Frontend UI
Main interface where user uploads resume and enters job description.

![Frontend UI](images/1_frontend.jpg)

---

## 🟡 2. Resume + Job Description Input
User provides CV and job description for analysis.

![Input Screen](images/2_cv_jd.png)

---

## 🔵 3. Submit & Settings Panel
System controls and configuration options.

![Settings Panel](images/3_settings.png)

---

## 🟣 4. Language Selection Feature
User can switch interface language.

![Language Options](images/4_language.png)

---

## ⚫ 5. Light / Dark Theme
UI theme customization feature.

![Theme Toggle](images/5_theme.png)

---

# 📈 Model Details
- TF-IDF Vectorizer
- Logistic Regression Classifier
- Text Classification Model

---

# 🚀 Installation

```bash
pip install -r requirements.txt
