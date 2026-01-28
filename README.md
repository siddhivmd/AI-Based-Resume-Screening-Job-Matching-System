# AI-Based-Resume-Screening-Job-Matching-System
✔ Resume–Job matching ✔ Match score (0–100%) ✔ Skill gap explanation (why matched / not matched)
🧠 AI-Based Resume Screening & Job Matching System
📌 Project Overview

Recruiters often spend a lot of time manually screening resumes, which is slow and error-prone.
This project automates resume screening and job matching using Natural Language Processing (NLP) and Machine Learning techniques.

The system analyzes resume text, converts it into numerical features, and calculates how well a resume matches a given job role or job description.

🎯 Objectives

Automate resume screening

Reduce recruiter effort and time

Rank resumes based on relevance

Provide a match score between resume and job description

🛠️ Technologies Used

Python

Pandas, NumPy – data handling

NLTK – text preprocessing

Scikit-learn

TF-IDF Vectorizer

Cosine Similarity

Machine Learning & NLP

📂 Dataset

The dataset contains:

Resume_html – resume content (text/HTML)

Category – job category or domain

Resume text contains unstructured data, making it ideal for NLP-based analysis.

🔄 Project Workflow

Load resume dataset

Clean and preprocess text

Remove stopwords and special characters

Convert text into TF-IDF vectors

Calculate similarity using cosine similarity

Generate a resume–job match score

Rank resumes based on relevance

🧹 Text Preprocessing

Lowercasing text

Removing special characters and numbers

Removing stopwords using NLTK

This improves the quality of text representation for ML models.

🧮 Feature Extraction

TF-IDF (Term Frequency–Inverse Document Frequency) is used to convert resumes and job descriptions into numerical vectors that represent the importance of words.

📊 Resume Matching Logic

Cosine Similarity is used to measure similarity between resume vectors and job description vectors.

Output is a match score (percentage).

Higher score = better match.

📈 Sample Output
Match Score: 82.45%


Resumes are ranked in descending order of relevance.
