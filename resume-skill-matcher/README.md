# 💼 AI Resume Skill Matcher

## 📌 Overview
An AI-powered system that recommends the best job role based on user skills using semantic similarity.

## 🚀 Features
- Skill-based job matching
- Semantic search using embeddings
- Fast and accurate recommendations

## 🧠 How It Works
1. Job roles and skills are converted into embeddings
2. User skills are converted into embedding
3. Cosine similarity finds best match
4. Most relevant job is returned

## ▶️ How to Run
pip install -r requirements.txt  
python app.py  

## 💬 Example
Input:
Python Machine Learning

Output:
Data Scientist

## 📷 Demonstration

![Output Screenshot](output.png)

## 🔗 Relation to Vector Databases
Simulates how vector databases like Endee:
- Store embeddings
- Perform similarity search
- Retrieve best results
