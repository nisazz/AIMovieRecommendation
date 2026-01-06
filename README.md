# 🎬 Smart Movie Recommendation System  
**BCCS1113 – Artificial Intelligence (Group Assignment)**

## 📌 Project Overview
This project implements a **Smart Movie Recommendation System** using **Artificial Intelligence techniques**, specifically **User-User Collaborative Filtering**.  
The system recommends movies to users based on their **past ratings and viewing preferences**, and can also generate **joint recommendations** for multiple users.

All implementation and experimentation were conducted using **Google Colab**, leveraging Python-based data science and recommendation libraries.

---

## 👥 Group Members
- **Hanisah**
- **Teo**
- **Hanif**
- **Uzayr**

---

## 🎯 Project Objectives
- Develop a simple AI-based movie recommendation system
- Recommend movies based on user viewing history and preferences
- Apply **collaborative filtering** techniques
- Support **individual** and **combined (group)** recommendations
- Demonstrate basic AI model training and evaluation workflow

---

## 🧠 System Description

The Smart Movie Recommendation System works by analyzing **user ratings data** and identifying patterns between users with similar preferences.

### Key Features:
- 📊 Uses real-world movie datasets (`movies.csv`, `ratings.csv`)
- 👤 Generates personalized recommendations for individual users
- 👥 Supports joint recommendations using combined user preferences
- 🎭 Optional filtering by movie genres
- 🤖 Implements **User-User Collaborative Filtering** using the **LensKit** library

The system simulates how streaming platforms recommend movies based on community behavior rather than explicit content analysis.

---

## ⚙️ Technologies & Tools Used
- **Python**
- **Google Colab**
- **Pandas**
- **LensKit (Collaborative Filtering Library)**
- **CSV Datasets**
- **GitHub (dataset hosting)**

---

## 🗂 Dataset Information
The system uses the following datasets:
- `movies.csv` – Movie titles and genres
- `ratings.csv` – User ratings data
- `jai-movie-ratings.csv` – Custom ratings for User 1
- `anep-movie-ratings.csv` – Custom ratings for User 2

Datasets are cloned directly from GitHub during runtime.

---

## 🧩 System Workflow

### 1️⃣ Environment Setup
- Install required libraries
- Clone dataset repository
- Import dependencies

### 2️⃣ Data Preparation
- Load movie and rating datasets
- Clean and structure user rating data
- Optional genre filtering

### 3️⃣ Model Configuration & Training
- Configure **User-User Collaborative Filtering**
- Train model using filtered ratings
- Set number of recommendations

### 4️⃣ Individual Recommendations
- Generate personalized movie recommendations for User 1
- Generate personalized movie recommendations for User 2

### 5️⃣ Joint Recommendations
- Combine ratings from both users
- Generate shared recommendations reflecting both preferences

---

## 🔁 Recommendation Approach
**Algorithm Used:**  
- User-User Collaborative Filtering

**Library:**  
- LensKit

**How It Works:**
- Finds users with similar rating patterns
- Predicts unseen movies based on neighbors’ preferences
- Ranks movies by predicted relevance

---

## 📓 Google Colab Notebook
All code and experiments are available in the Google Colab notebook:

👉 **Colab Notebook Link:**  
`https://colab.research.google.com/drive/1VGyr3Puy2PtpUmnO4qi1MUhOsM-zNKuV?usp=sharing`

> ⚠️ Note: No source code is stored directly in this repository.  
> The repository serves as **documentation and project reference**.

---

## 📁 Repository Purpose
This GitHub repository contains:
- Project documentation
- System explanation
- Assignment reference
- Link to Google Colab implementation

---

## ✅ Learning Outcomes
- Understanding collaborative filtering techniques
- Applying AI concepts to recommendation systems
- Handling real-world datasets
- Using Google Colab for AI experimentation
- Translating user behavior into intelligent predictions

---

## 📜 License
This project is created for **educational purposes only** as part of a university assignment.

---
