# SMS-Email_Spam_Classification

# 📧 SMS/Email Spam Classifier

A machine learning–powered web app to classify SMS and Email messages as **Spam** or **Not Spam**.  
Built with **Python, scikit-learn, Streamlit**, and deployed on **Heroku** (coming soon 🚀).

---

##  Features
- Preprocesses input text (lowercasing, tokenization, stopword removal, stemming).
- Uses **TF-IDF vectorization** for feature extraction.
- Trained with **Multinomial Naive Bayes** (best-performing model in experiments).
- Simple **Streamlit UI** for real-time classification.
- Ready for deployment on **Heroku**.

---

##  Tech Stack
- **Python 3.x**
- **Pandas / NumPy** – Data handling
- **NLTK** – Text preprocessing
- **scikit-learn** – ML model (MultinomialNB) & vectorizer
- **Streamlit** – Web app
- **Pickle** – Model & vectorizer persistence
- **Heroku** – Deployment target

---

##  Project Structure
- ├── app.py # Streamlit app
├── SMS_SPAM.ipynb # Notebook for training and experimentation
├── model.pkl # Trained MultinomialNB model
├── vectorizer.pkl # Saved TF-IDF vectorizer
├── requirements.txt # Dependencies
└── README.md # Project documentation
