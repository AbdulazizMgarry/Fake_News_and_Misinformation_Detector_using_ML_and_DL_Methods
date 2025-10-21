# SIC_AI
# 🧠 Fake News & Misinformation Detector

An intelligent system that detects fake and misleading news using both **Machine Learning** and **Deep Learning** techniques.  
Developed as a **Samsung Innovation Campus Capstone Project** by **Vision Group**.

---

## 📘 Introduction

Fake news spreads quickly across social media and can distort public opinion.  
Our system identifies whether a piece of news is **real or fake** using NLP-based text analysis and AI models.

---

## ⚙️ Solution Overview

**Dataset:** [Kaggle - Fake News Classification](https://www.kaggle.com)  
**Techniques Used:**
- Data Cleaning and Preprocessing  
- Feature Extraction using **TF-IDF** and **Word2Vec**
- Model Training with:
  - Logistic Regression  
  - Support Vector Machine (SVM)  
  - Long Short-Term Memory (LSTM)
- Evaluation using:
  - Accuracy, Precision, Recall, F1-score  
  - Confusion Matrix and ROC Curve  

---

## 🧩 Project Workflow

1. **Data Collection:** Import Kaggle dataset  
2. **Preprocessing:** Clean, tokenize, and normalize text  
3. **Feature Extraction:** Create numerical representations  
4. **Modeling:** Train and validate ML and DL models  
5. **Evaluation:** Compare performance and visualize metrics  

---

## 📊 Model Results

| Model | Accuracy | Precision | Recall |
|--------|-----------|------------|---------|
| Logistic Regression | 0.94 | 0.93 | 0.94 |
| SVM | 0.95 | 0.95 | 0.95 |
| LSTM | **0.96** | **0.96** | **0.96** |

**LSTM achieved the best overall performance.**

---

## 📈 Visual Results

| Visualization | Description |
|----------------|-------------|
| ![model comparison]([Photos/model_comparison.png](https://github.com/AbdulazizMgarry/SIC_AI/blob/main/model_comparison.png)) | Accuracy comparison of all models |


---

## 💡 Applications & Future Work

**Applications:**
- Help media outlets verify content before publishing  
- Detect misinformation across social platforms  
- Develop browser extensions for real-time fake news checks  

**Future Enhancements:**
- Support for multi-language datasets  
- Integration with live news feeds  
- Deployment as a public web app  

---

## 🛠️ Tech Stack

- **Languages:** Python  
- **Libraries:** Pandas, NumPy, Scikit-learn, TensorFlow/Keras, NLTK, Matplotlib, Seaborn  
- **Tools:** Jupyter Notebook, Google Colab  
- **Dataset Source:** Kaggle  

---

## 🧾 License

This project is licensed under the **MIT License** — you are free to use and modify it with attribution.

---

## 🙏 Acknowledgements

- **Samsung Innovation Campus**  
- **Kaggle** for dataset access  
- Mentors and teammates for collaboration
