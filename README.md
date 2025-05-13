# 🛡️ Cyberbullying Detection using Machine Learning

This project is a web-based application that detects cyberbullying in text using machine learning techniques. The aim is to support online safety and digital well-being by providing real-time classification of harmful content.


## 🚀 Features

- 🧠 Machine Learning Model ('Passive Aggressive', 'XGBoost', 'Random Forest', 'Multinomial Naive Bayes')
- 💬 Text classification: Detects whether a message is cyberbullying or not
- 📊 Real-time inference through a clean and interactive Streamlit web app
- 📁 Preprocessing using NLP techniques: Tokenization, Stopwords Removal, TF-IDF
- 🛠️ Easily extendable for other text classification tasks

---

## 🧰 Tech Stack

- Python 3.8+
- Streamlit – for web UI
- Scikit-learn – for ML model training and inference
- NLTK – for text preprocessing
- Pandas, NumPy – for data handling
- Jupyter Notebook – for model training

---

## 📁 Project Structure

-Cyberbullying_Prediction.ipynb
-Streamlit_App.py
-config.toml
-count_vectorizer.pkl
-cyberbullying_tweets.csv
-test_predictions.csv
-xgb_model.pkl
-README.md

## Getting Started

1️⃣ Clone the Repository

2️⃣ Create Virtual Environment (optional but recommended)
python -m venv venv
venv\Scripts\activate      # On Windows
source venv/bin/activate   # On Mac/Linux

3️⃣ Install Dependencies
Run the jupyter notebook to install all the required depemdencies-- Cyberbullying_Prediction.ipynb

4️⃣ Run the Streamlit App
streamlit run Streamlit_App.py
Or, if streamlit is not in your PATH:
python -m streamlit run Streamlit_App.py

📄 License
This project is licensed under the MIT License.

🤝 Contributing
Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

👨‍💻 Author
Aerupilli Krishnamraju

LinkedIn: https://www.linkedin.com/in/aerupilli-krishnamraju/
GitHub: https://github.com/KrishnamrajuAerupilli/

