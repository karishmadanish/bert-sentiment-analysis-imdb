
# 🎭 BERT-Based Sentiment Analysis on IMDb Reviews

This project implements a **context-aware sentiment analysis** system using **BERT (Bidirectional Encoder Representations from Transformers)**. It classifies movie reviews as **positive** or **negative** with strong accuracy by understanding contextual phrases like *"not happy"* or *"wasn't good"* — something traditional ML models often fail at.

---

## 🚀 What This Project Covers

- ✅ IMDb movie review dataset
- ✅ Pretrained BERT model (`bert-base-uncased`)
- ✅ Tokenization and padding
- ✅ Fine-tuning BERT using HuggingFace `Trainer`
- ✅ Custom input predictions
- ✅ Ready for deployment (Streamlit / web app compatible)

---

## 📂 Dataset

- 📦 **IMDb** dataset (from [Hugging Face Datasets](https://huggingface.co/datasets/imdb))
- 50,000 reviews → 25,000 training + 25,000 test
- Balanced binary classification: `Positive (1)` / `Negative (0)`

---

## 🧠 Technologies Used

| Tool / Library         | Purpose                         |
|------------------------|--------------------------------|
| `transformers`         | Pretrained BERT model + Trainer |
| `datasets`             | IMDb dataset loading             |
| `sklearn`              | Accuracy evaluation              |
| `PyTorch`              | Model backend                    |

---

## 🧪 Sample Predictions

```python
predict_sentiment("I didn't like the movie.")     # → Negative 😞
predict_sentiment("Absolutely loved the plot!")   # → Positive 😊
predict_sentiment("Not happy with the ending.")   # → Negative 😞
```

---

## 📊 Accuracy

- Trained on a **smaller sample (4K train, 1K test)** for fast performance in notebooks
- Accuracy: ~90% on test split (varies slightly by run)

> You can train on the **full 25K dataset** for higher accuracy if needed.

---

## 🛠 How to Run

### ▶️ In Google Colab

1. Upload `BERT_Sentiment_Analysis_IMDb.ipynb` to your Colab
2. Run each cell step-by-step
3. Use the final cell to enter a custom review and get predictions

---

## 🌐 Future Improvements

- Add a Streamlit web app for real-time predictions
- Save and deploy model via `Hugging Face Hub` or `Flask API`
- Train on full dataset or use distilled BERT for faster inference

---

## 🧑‍💻 Author

**Karishma Danish**  
_BCA Fresher passionate about AI/ML and NLP_  
[LinkedIn](https://linkedin.com/in/karishmadanish) | [GitHub](https://github.com/karishmadanish) | [Email](karishmadanish265@gmail.com)

---

## 📌 Keywords

`BERT` · `NLP` · `Sentiment Analysis` · `IMDb Dataset` · `Python` · `Transformers` · `Fine-tuning` · `Hugging Face` · `Machine Learning`
