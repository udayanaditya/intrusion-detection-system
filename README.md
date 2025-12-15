# Intrusion Detection System (IDS)

## 📌 Project Overview

This project implements a **Machine Learning–based Intrusion Detection System (IDS)** designed to identify malicious network traffic and potential cyber-attacks. The system leverages the **CICIDS 2017 dataset** and applies a **Random Forest classifier** to detect multiple types of network intrusions with high accuracy.

The goal of this project is to enhance network security by automatically classifying network flows as **benign or malicious**, helping organizations proactively defend against cyber threats.

---

## 🚀 Features

* Detection of multiple network attacks (e.g., DoS, DDoS, SQL Injection, Brute Force)
* Uses **70+ network traffic features** for robust classification
* Machine learning–based approach using **Random Forest**
* Data preprocessing and feature selection
* Model evaluation using standard performance metrics
* Implemented fully in **Python** using Jupyter Notebook

---

## 🧠 Machine Learning Approach

* **Algorithm Used:** Random Forest Classifier
* **Reason for Choice:**

  * Handles high-dimensional data efficiently
  * Resistant to overfitting
  * Provides good accuracy for structured datasets

---

## 📂 Dataset

* **Dataset Name:** CICIDS 2017
* **Source:** Canadian Institute for Cybersecurity
* **Description:**

  * Contains real-world benign and malicious network traffic
  * Includes labeled attack categories such as:

    * DoS
    * DDoS
    * SQL Injection
    * Brute Force
    * Port Scan

---

## 🛠️ Technologies Used

* **Programming Language:** Python
* **Libraries & Tools:**

  * NumPy
  * Pandas
  * Scikit-learn
  * Matplotlib / Seaborn
  * Jupyter Notebook

---

## ⚙️ Project Workflow

1. Data Loading and Cleaning
2. Feature Selection and Preprocessing
3. Train-Test Split
4. Model Training using Random Forest
5. Model Evaluation
6. Result Visualization

---

## 📊 Evaluation Metrics

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

These metrics help assess the effectiveness of the IDS in detecting attacks while minimizing false positives.

---

## ▶️ How to Run the Project

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/intrusion-detection-system.git
   ```
2. Navigate to the project directory:

   ```bash
   cd intrusion-detection-system
   ```
3. Install required dependencies:

   ```bash
   pip install -r requirements.txt
   ```
4. Open the Jupyter Notebook:

   ```bash
   jupyter notebook intrusion-detection-system.ipynb
   ```
5. Run all cells sequentially.

---

## 📈 Results

* Achieved high accuracy in detecting malicious traffic
* Random Forest performed effectively on high-dimensional network data
* Demonstrated strong capability in identifying DoS and DDoS attacks

---

## 🔮 Future Enhancements

* Integration with real-time network traffic
* Deployment as a web-based monitoring system
* Comparison with other ML/DL models (XGBoost, Neural Networks)
* Feature importance visualization

---

## 👨‍💻 Author

**Udayan Aditya**
B.Tech Computer Science Engineering
Full Stack Developer | Machine Learning Enthusiast

---

## 📜 License

This project is intended for **academic and educational purposes**.

---

⭐ If you find this project useful, feel free to star the repository!
