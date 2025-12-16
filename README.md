# Email_Sms_Spam_Classifier
👇
📧 Email / SMS Spam Classifier

An intelligent Email and SMS Spam Classification system built using Machine Learning and Natural Language Processing (NLP). This project automatically detects whether a message is Spam or Not Spam (Ham) by analyzing its textual content.

🚀 Features

Classifies Email and SMS messages as Spam or Ham

Text preprocessing: lowercase conversion, tokenization, stopword removal, stemming

TF-IDF Vectorization for feature extraction

Machine Learning model trained on labeled spam datasets

Simple and interactive web-based interface

Fast and accurate real-time prediction


🧠 Technologies Used

Python

Scikit-learn

Natural Language Toolkit (NLTK)

TF-IDF Vectorizer

Flask / Streamlit (for UI)

Pickle (model serialization)

📁 Project Structure
 <pre> Email-SMS-Spam-Classifier/
│
├── app.py                  # Main application file
├── model.pkl               # Trained ML model
├── vectorizer.pkl          # TF-IDF vectorizer
├── requirements.txt        # Project dependencies
├── README.md               # Project documentation
│
├── static/                 # CSS, images (Flask)
├── templates/              # HTML files (Flask)
│
└── notebook/
    └── training.ipynb      # Model training notebook
</pre>

Run the Application
<pre> Python app.run<pre>
⚙️ Project Workflow

User enters an Email or SMS message

Text preprocessing (lowercase, tokenization, stopwords removal, stemming)

TF-IDF converts text into numerical features

ML model predicts Spam or Not Spam

Result is displayed on the web interface


