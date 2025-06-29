# 📱 Google Play Store Data Analysis & Feature Engineering

### Author: Vaishnavi Awasthi  
🔗 GitHub: [@awasthivaishnavi](https://github.com/awasthivaishnavi)

---

## 📝 Project Overview

This project focuses on performing **Exploratory Data Analysis (EDA)** and **Feature Engineering (FE)** on the [Google Play Store dataset](https://www.kaggle.com/datasets/lava18/google-play-store-apps). The goal is to extract insights about app performance, popularity, size, and ratings to help understand trends in the app market.

With over 2.5 million apps on the Play Store, this dataset offers valuable insight into app types, installs, pricing models, and user engagement.

---

## 📊 Problem Statement

Our main objectives:

- Identify the **most popular app category**
- Find the app with the **highest number of installs**
- Determine the **app with the largest size**
- Clean and prepare the data for analysis and future modeling

---

## 📁 Dataset Summary

- 📦 **Rows:** 10,841  
- 🧾 **Columns:** 20  
- Data includes app name, category, rating, reviews, size, installs, type (Free/Paid), price, content rating, genres, last updated, etc.

---

## 🔍 Steps Performed

### ✅ 1. Data Cleaning
- Removed missing, duplicate, or erroneous entries
- Converted size and install columns into numeric format
- Handled outliers and inconsistent formatting

### ✅ 2. Exploratory Data Analysis (EDA)
- Visualized:
  - Distribution of categories
  - App rating vs. number of reviews
  - Size vs. Installs
  - Free vs. Paid app comparison
- Used seaborn, matplotlib, and pandas for data visualization

### ✅ 3. Feature Engineering
- Extracted and converted relevant features for analysis
- Created new variables like `size_MB`, `is_free`, and `log_reviews`
- Prepared dataset for machine learning or deeper statistical analysis

---

## 📌 Key Insights

- The **"Family"** category has the highest number of apps.
- **"Google Play Services"** and **"WhatsApp Messenger"** are among the most installed apps.
- Larger apps don’t always have more installs.
- Most apps are **free**, with a few **paid apps** priced above $100 (often errors or niche).

---

## 💻 Technologies Used

- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Jupyter Notebook
- Data source: [Kaggle Google Play Store Dataset](https://www.kaggle.com/datasets/lava18/google-play-store-apps)

---

## 📂 Folder Structure

Google-Playstore-EDA/
├── 3.0-EDA-And-FE-Google-Playstore.ipynb
├── README.md

---

## 🚀 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/awasthivaishnavi/Google-Playstore-EDA.git
   cd Google-Playstore-EDA

Launch the notebook:

jupyter notebook 3.0-EDA-And-FE-Google-Playstore.ipynb

📞 Contact
If you have questions or want to collaborate, feel free to connect:

Vaishnavi Awasthi
📧 Email: vaishnaviawasthi70@gmail.com
🌐 GitHub: @awasthivaishnavi
