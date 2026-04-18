# 📰 Arabic Fake News Detection Pipeline

This project implements a Machine Learning pipeline to detect and classify Arabic fake news using **Support Vector Machines (SVM)**.

### 🛠️ Technical Implementation
The project uses a structured approach to process and classify Arabic text:
* **Vectorization:** `TfidfVectorizer` to convert Arabic text into numerical features.
* **Classifier:** `LinearSVC` (Support Vector Machine) for high-performance text classification.
* **Pipeline:** Utilizes Scikit-learn's `Pipeline` to streamline the vectorization and training process.

### 🚀 Features
* Automated preprocessing and feature extraction.
* Optimized for Arabic text classification.
* Clean and modular Python implementation in `ber.py`.

### 💻 Requirements
* Python 3.x
* Scikit-learn
* Pandas
