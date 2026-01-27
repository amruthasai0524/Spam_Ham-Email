Spam–Ham Email Classifier 

A Machine Learning web application that classifies emails/messages as Spam or Ham (Not Spam) using Natural Language Processing (NLP) and Scikit-learn, deployed with Streamlit for real-time predictions.

 Features

Text preprocessing & cleaning

TF-IDF vectorization

ML model training (Naive Bayes / Logistic Regression)

Real-time spam prediction

Interactive Streamlit UI

Lightweight & fast deployment

🛠️ Tech Stack

Python

Pandas, NumPy

Scikit-learn

NLP (TF-IDF)

Streamlit

 Project Structure
spam-ham-classifier/
│
├── app.py                # Streamlit app
├── model.pkl             # Trained ML model
├── vectorizer.pkl        # TF-IDF vectorizer
├── dataset.csv           # Email dataset
├── requirements.txt
└── README.md

 Installation

Clone the repository:

git clone https://github.com/your-username/spam-ham-classifier.git
cd spam-ham-classifier


Install dependencies:

pip install -r requirements.txt

 Run the App
streamlit run app.py


Open browser:

http://localhost:8501

 How It Works

Clean & preprocess text

Convert text → TF-IDF vectors

Train ML model

User inputs message

Model predicts Spam or Ham

📸 Demo

Type any email/message → Get instant prediction.

Example:

Congratulations! You won $1000
➡ Spam

📈 Future Improvements

Deep learning models (LSTM/BERT)

Email file upload (.eml)

Deployment on cloud (Streamlit Cloud/Heroku)

Accuracy optimization
