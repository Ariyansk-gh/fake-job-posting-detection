# Fake Job Posting Detection using Machine Learning

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Classification-green)
![NLP](https://img.shields.io/badge/NLP-TF--IDF-orange)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-red)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

##  Project Overview

The Fake Job Posting Detection System is a Machine Learning and Natural Language Processing (NLP) project designed to identify fraudulent job advertisements. With the increasing number of online recruitment scams, this project helps job seekers and recruitment platforms distinguish between genuine and fake job postings.

The model analyzes job descriptions and related information to predict whether a job posting is legitimate or fraudulent, improving trust and security in online hiring platforms.

---

##  Problem Statement

Fake job advertisements can lead to:

- Financial fraud
- Identity theft
- Data theft
- Loss of time and resources

This project aims to develop an intelligent classification model capable of detecting fake job postings accurately and efficiently.

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-Learn
- NLTK
- Matplotlib
- Seaborn
- Jupyter Notebook

---

##  Dataset

The dataset contains job posting information including:

- Job Title
- Company Profile
- Job Description
- Requirements
- Benefits
- Employment Type
- Industry
- Function
- Location
- Fraudulent Label

### Target Variable

| Label | Meaning |
|---------|---------|
| 0 | Genuine Job Posting |
| 1 | Fake Job Posting |

---

##  Project Workflow

```text
Data Collection
      ↓
Data Cleaning
      ↓
Text Preprocessing
      ↓
Feature Extraction (TF-IDF)
      ↓
Model Training
      ↓
Model Evaluation
      ↓
Fake Job Prediction
```

---

##  Data Preprocessing

The following preprocessing techniques were applied:

- Handling Missing Values
- Removing Irrelevant Features
- Text Cleaning
- Lowercasing
- Stopword Removal
- Tokenization
- Feature Engineering
- TF-IDF Vectorization

---

##  Machine Learning Approach

The project uses Machine Learning algorithms to classify job postings as real or fake.

### Key Steps:

- Data Preparation
- Text Vectorization using TF-IDF
- Model Training
- Model Evaluation
- Fraud Detection Prediction

---

##  Evaluation Metrics

Model performance is evaluated using:

- Accuracy Score
- Precision
- Recall
- F1 Score
- Confusion Matrix

These metrics help assess how effectively the model identifies fraudulent job advertisements.

---

##  Key Features

✔ Detects Fake Job Advertisements

✔ Uses Natural Language Processing (NLP)

✔ Text Feature Extraction using TF-IDF

✔ Machine Learning Based Classification

✔ Performance Evaluation Metrics

✔ Real-World Fraud Detection Use Case

---

##  Project Structure

```text
fake-job-posting-detection/
│
├── Fake Jobs posting Detection.ipynb
├── dataset/
│   └── fake_job_postings.csv
├── images/
│   ├── workflow.png
│   ├── confusion_matrix.png
│   └── results.png
├── requirements.txt
├── README.md
└── .gitignore
```

---

##  Future Enhancements

- Streamlit Web Application Deployment
- Real-Time Fake Job Detection
- Deep Learning Integration
- REST API Development
- Resume Matching System
- AI-Based Job Recommendation System

---

##  Business Impact

This project can help:

- Job Seekers avoid fraudulent opportunities
- Recruitment Platforms improve trustworthiness
- HR Teams validate job postings automatically
- Organizations reduce recruitment fraud

---

##  Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/fake-job-posting-detection.git
```

Navigate to the project folder:

```bash
cd fake-job-posting-detection
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run Jupyter Notebook:

```bash
jupyter notebook
```

---

##  Repository Topics

```text
machine-learning
data-science
nlp
fake-job-detection
fraud-detection
classification
python
scikit-learn
data-analysis
job-postings
```

---

## Dataset

The dataset used for this project is not included in this repository due to GitHub file size limitations.

Users can download the dataset from Kaggle:
https://www.kaggle.com/datasets/shivamb/real-or-fake-fake-jobposting-prediction

## 👨‍💻 Author

### Ariyan Shaikh

B.Sc. Information Technology Graduate

Aspiring Data Scientist | Machine Learning Enthusiast | Python Developer

📧 Email: ariyanshaikh2004@gmail.com

🔗 LinkedIn: https://www.linkedin.com/in/ariyan-shaikh-7553793b1/

🔗 GitHub: https://github.com/Ariyansk-gh

---

## ⭐ Support

If you found this project useful, please consider giving it a ⭐ on GitHub.

It helps others discover the project and motivates further improvements.
