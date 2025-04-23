
# 📄 Resume Screening System using BiLSTM and NLP

This project aims to automate resume classification into job categories using deep learning and NLP. It helps in streamlining the HR screening process and demonstrates real-world use of Bidirectional LSTM for multi-class text classification.

---

## 📊 Dataset

- **Source**: [Resume Dataset from Kaggle](https://www.kaggle.com/datasets/iamanshul/resume-dataset)
- **Features**: Resume Text (`Resume_str`)
- **Target**: Job Category (`Category`)
- Total Classes: 25+

---

## 🧠 Techniques Used

- Text Preprocessing with NLTK (cleaning, tokenization, stopword removal)
- Word vectorization with **Tokenizer** and padding with `pad_sequences`
- **Deep Learning model** with:
  - `Embedding` layer for learning semantic word representations
  - `Bidirectional LSTM` for contextual learning
  - `Dense + Softmax` for multi-class classification

---

## 🛠️ Libraries & Tools

- Python
- Pandas, NumPy
- NLTK (text preprocessing)
- TensorFlow/Keras (deep learning)
- scikit-learn (metrics, label encoding)
- Matplotlib & Seaborn (visualization)

---

## 📈 Model Performance

- **Architecture**: Embedding + BiLSTM + Dense
- **Evaluation Metrics**:
  - Accuracy: ~85%
  - Precision, Recall, F1-Score (multi-class)
- **Insights**:
  - Model performs best on common categories like Data Scientist, Web Developer
  - Confusion matrix reveals class overlaps in similar job types

---

## 🗂 Project Structure

```
resume_screening_bilstm/
├── resume.json
├── resume_screening_bilstm.ipynb
├── requirements.txt
└── README.md
```

---

## ✅ How to Run

1. Clone the repo
2. Install requirements: `pip install -r requirements.txt`
3. Run the notebook: `resume_screening_bilstm.ipynb`

---

## 📌 Author

**Shaurya Chauhan**  
Aspiring Data Analyst | Economics Graduate | Deep Learning Enthusiast  
[LinkedIn](https://www.linkedin.com/in/shaurya-chauhan-0089911bb/) | [GitHub](https://github.com/yourgithub)

---
