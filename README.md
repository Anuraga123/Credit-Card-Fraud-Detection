<h1 align="center">💳 Credit Card Fraud Detection</h1>
<p align="center">
  <b>A Machine Learning + Django Web App to detect fraudulent credit card transactions</b><br>
  <i>Built using Python, Scikit-learn, SQL, HTML/CSS, and XAMPP</i>
</p>

<p align="center">
  <img src="https://img.shields.io/github/stars/Anuraga123/Credit-Card-Fraud-Detection?style=social" />
  <img src="https://img.shields.io/github/forks/Anuraga123/Credit-Card-Fraud-Detection?style=social" />
  <img src="https://img.shields.io/github/issues/Anuraga123/Credit-Card-Fraud-Detection" />
  <img src="https://img.shields.io/github/license/Anuraga123/Credit-Card-Fraud-Detection" />
</p>

---

## 📌 Overview

This project aims to detect fraudulent credit card transactions using machine learning techniques. It includes a web interface where users can input transaction data and receive real-time fraud detection results.

The backend is powered by a Logistic Regression model trained on the Kaggle dataset. The frontend is styled with HTML/CSS, and the entire app is served via Django, with a simple SQLite database and XAMPP for local development.

---


---

## 🚀 Features

- 🧠 ML-based Fraud Detection (Logistic Regression)
- 🌐 Web interface built with Django
- 📦 REST-style prediction and admin panel
- 💾 SQLite DB for lightweight usage
- 📊 Kaggle Dataset for training
- 🔐 Superuser authentication

---

## 📷 Screenshots

### 🔹 1. Admin Login Page  
Secure login interface for admin access.

<img src="screenshots/login.png" alt="Admin Login" width="700"/>

---

### 🔹 2. Single Record Prediction  
Interface to enter and test one transaction at a time.

<img src="screenshots/single record.png" alt="Single Record Prediction" width="700"/>

---

### 🔹 3. Multiple Record Upload  
Upload a file to test fraud on multiple transactions.

<img src="screenshots/multirecord.png" alt="Multiple Record Upload" width="700"/>

---

### 🔹 4. Fraud Analysis Dashboard  
Graphical insights into fraud trends and results.

<img src="screenshots/aqnalysis.png" alt="Analysis Dashboard" width="700"/>


## 🔗 Dataset

This project uses the public Kaggle dataset:  
📎 [Credit Card Fraud Detection Dataset – Kaggle](https://www.kaggle.com/mlg-ulb/creditcardfraud)

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repo

```bash
git clone https://github.com/Anuraga123/Credit-Card-Fraud-Detection.git
cd Credit-Card-Fraud-Detection

###2️⃣ Create & Activate Virtual Environment
# Install virtualenv if not installed
pip install virtualenv

# Create environment
virtualenv venv

# Activate it
venv\Scripts\activate   # Windows
source venv/bin/activate  # Mac/Linux

###3️⃣ Install Requirements
pip install -r requirements.txt


###4️⃣ Apply Migrations
python manage.py makemigrations
python manage.py migrate

###5️⃣ Create Superuser
python manage.py createsuperuser

###6️⃣ Run Server
python manage.py runserver

⭐ If you liked this project, give it a star!



