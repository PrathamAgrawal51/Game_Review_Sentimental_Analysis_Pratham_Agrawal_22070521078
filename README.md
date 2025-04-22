# 🎮 Steam Game Review Sentiment Analysis

A machine learning project that analyzes user reviews of Steam games to predict whether the sentiment is **positive** or **negative**. This project leverages Natural Language Processing (NLP) techniques to transform textual data into valuable insights.

---

## 😊 Collaborators

- Pratham Agrawal (22070521078)
- Devanshu Sawarkar (22070521090)
- Devansh Motghare (22070521076)

---

## 📌 Features

- Clean and preprocess Steam game reviews
- Tokenize and vectorize textual data using **TF-IDF**
- Train and evaluate multiple classifiers (Logistic Regression, Naive Bayes, etc.)
- Display metrics like **accuracy**, **confusion matrix**, and **classification report**
- Visualize performance with **matplotlib** and **seaborn**

---

## 🧠 Model Workflow

1. **Data Preprocessing**
   - Removing punctuations, stopwords
   - Lowercasing, tokenization
   - TF-IDF Vectorization

2. **Model Training**
   - Logistic Regression
   - Multinomial Naive Bayes
   - Random Forest

3. **Evaluation**
   - Accuracy
   - Confusion Matrix
   - Classification Report

---

## 🔧 Technologies Used

- Python 3
- Pandas, NumPy
- Scikit-learn
- NLTK
- Matplotlib, Seaborn

---

## 📊 Example Output

```
Multinomial Naive Bayes Accuracy: 84%
Support Vector Machine Accuracy: 86%
```

Confusion Matrix and classification metrics are displayed to evaluate model performance.

---

## 📁 Project Structure

```
📦Steam Game Review Sentiment Analysis
 ┣ 📓 Game_Review_Sentimental_Analysis.ipynb
 ┗ 📜 README.md
```

---

## 🚀 How to Run

1. Clone this repo:
   ```bash
   git clone https://github.com/PrathamAgrawal51/Game_Review_Sentimental_Analysis_Pratham_Agrawal_22070521078.git
   cd steam-review-sentiment-analysis
   ```

2. Open and run the notebook:
   ```bash
   jupyter notebook Game_Review_Sentimental_Analysis.ipynb
   ```

---

## 🧪 Sample Data

You can use any dataset containing Steam reviews with text and sentiment labels. Make sure the data is cleaned or preprocessed similarly as shown in the notebook.

---

## 📌 Future Work

- Deploy as a web app using **Flask/Streamlit**
- Use **deep learning models** like LSTM
- Add more visual insights (word clouds, game-wise sentiment distribution)

---

## 🙌 Acknowledgements

Thanks to the open-source community and datasets from Kaggle and Steam APIs.

---

## 📬 Contact

For any feedback or suggestions, feel free to reach out!
