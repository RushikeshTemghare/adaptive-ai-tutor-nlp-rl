# Adaptive AI Tutor using NLP & Reinforcement Learning

## 📌 Overview

This project presents an intelligent tutoring system developed as part of my MSc in Data Science & Artificial Intelligence.

The system is designed to personalise learning experiences by analysing learner performance data and dynamically recommending appropriate educational content using machine learning and reinforcement learning techniques.

The objective was to build an adaptive AI framework capable of:
- Segmenting learners
- Predicting learning outcomes
- Optimising content recommendations
- Evaluating generated explanations using NLP metrics

---

## 🧠 Methodology

### 1️⃣ Learner Profiling
- KMeans clustering used to segment learners based on performance features.

### 2️⃣ Reinforcement Learning
- Deep Q-Network (DQN) implemented within a custom environment.
- Reward-based optimisation for adaptive content delivery.

### 3️⃣ Supervised Learning Models
- Logistic Regression
- Random Forest
- Gradient Boosting

Models were evaluated using accuracy and classification metrics.

### 4️⃣ NLP Evaluation
- BLEU Score
- ROUGE-L Score
- Text similarity metrics

---

## 📊 Key Results

| Model | Accuracy |
|--------|----------|
| Logistic Regression | 0.509 |
| Random Forest | 0.49 |
| Gradient Boosting | 0.47 |

ROUGE-L score improved to 0.625 after optimisation.

---

## 🛠 Tech Stack

- Python
- Scikit-learn
- TensorFlow / PyTorch
- OpenAI Gym
- NLTK
- Pandas & NumPy
- Matplotlib

---

## 📂 Repository Structure

adaptive-ai-tutor-nlp-rl/
│
├── notebooks/
│ └── Final_Code.ipynb
├── data/
│ └── papers3.csv
├── docs/
│ └── Dissertation_Report.pdf
├── requirements.txt
└── README.md


---

## 🚀 Future Improvements

- Transformer-based NLP models
- Real-time deployment via Streamlit
- Enhanced learner behaviour tracking
- Improved model performance through feature engineering

---

## 👨‍💻 Author

Rushikesh Temghare  
MSc Data Science & Artificial Intelligence  
Bournemouth University  
