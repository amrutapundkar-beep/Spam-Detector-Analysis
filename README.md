# Spam-Detector-Analysis
A machine learning project that classifies SMS messages as spam or ham using NLP techniques and multiple ML algorithms.


## 🌟 Introduction
In today’s digital world, SMS messages are widely used for communication, banking alerts, promotions, and notifications. However, the increasing number of **spam messages**—such as advertisements, fake prize alerts, and fraud schemes—creates inconvenience and security risks for users.

This project focuses on building an **intelligent SMS Spam Detection system** using **Natural Language Processing (NLP)** and **Machine Learning** to automatically classify messages as **Spam** or **Ham (Not Spam)**.

---

## 🎯 Problem Statement
To design and implement a machine learning model that can accurately classify SMS messages as **spam** or **ham** based on their textual content.

---

## 📖 Project Description
The SMS Spam Detection system analyzes the text of SMS messages and identifies patterns commonly found in spam messages.  
Using **NLP techniques**, the raw text is cleaned, processed, and converted into numerical features. These features are then used to train multiple **machine learning classifiers**.

Different algorithms are evaluated, and the best-performing model is selected based on accuracy.

This project demonstrates real-world application of:
- Text preprocessing  
- Feature extraction  
- Supervised machine learning  
- Model comparison and evaluation  

---

## 📂 Dataset Information
This project uses the **SMS Spam Collection Dataset**, a benchmark dataset widely used for spam detection research.

### Dataset Details:
- Total messages: **5,574**
- Language: **English**
- Classification type: **Binary**

### Labels:
- **Ham** – Legitimate, normal messages  
- **Spam** – Unwanted, promotional, or fraudulent messages  

The dataset contains real SMS messages collected for academic research and model training.

🔗 **Dataset Source:**  
https://www.kaggle.com/uciml/sms-spam-collection-dataset  

---

## 🧾 Attributes
- **Message** → Text content of the SMS  
- **Label** → spam / ham  

---

## 🛠️ Technologies & Libraries Used
- **Python**
- **Pandas** – Data handling and analysis  
- **NumPy** – Numerical operations  
- **NLTK** – Text preprocessing  
- **Regular Expressions (re)** – Text cleaning  
- **Scikit-learn** – Machine learning models  

---

## ⚙️ Project Workflow
1. Load and explore the dataset  
2. Clean text (remove symbols, stopwords, punctuation)  
3. Convert text into numerical vectors  
4. Train multiple machine learning models  
5. Evaluate models using accuracy  
6. Select the best-performing model  

---

## 🤖 Machine Learning Algorithms Used
- **Logistic Regression**
- **Naive Bayes**
- **Support Vector Classifier (SVC)**
- **Random Forest**

Each model was trained and tested to compare performance.

---

## 📊 Model Performance
- **Best Model Accuracy:** **98.27%**

This shows that machine learning combined with NLP can effectively detect spam messages with high accuracy.

---

## 📌 Output
The system classifies incoming SMS messages as:
- ✅ **Ham (Not Spam)**
- 🚫 **Spam**

---

## 🚀 Applications
- Mobile SMS spam filtering  
- Fraud and scam message detection  
- Email and message classification systems  
- Customer communication security  

---

## 💡 Key Learnings
- Text preprocessing is crucial for NLP tasks  
- Feature extraction directly impacts model accuracy  
- Comparing multiple models helps in selecting the best solution  
- NLP and ML together solve real-world problems effectively  

---

## 🏁 Conclusion
This project successfully demonstrates how **Natural Language Processing and Machine Learning** can be used to build an efficient SMS Spam Detection system. With an accuracy of **98.27%**, the model proves to be reliable and practical for real-world applications.

---

## 👩‍💻 Author
**Amruta Pundkar**   
Aspiring Data Analyst  
amrutapundkar2004@gmail.com
---

⭐ If you find this project useful, feel free to star the repository!
