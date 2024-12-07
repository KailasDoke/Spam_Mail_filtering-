Spam Email Classification using NLP and Machine Learning
Introduction
This project focuses on building a robust spam email classification system using Natural Language Processing (NLP) and Machine Learning. By leveraging techniques such as text preprocessing, Bag-of-Words (BoW) feature extraction, and a Multinomial Naive Bayes classifier, the system accurately distinguishes between spam and non-spam emails.

The project includes two user-friendly deployment platforms:

A desktop application built with Tkinter.
A web-based application powered by Streamlit.
Features
Classifies emails as Spam or Not Spam.
Speech notification feature (for Tkinter application).
Lightweight and efficient model for quick predictions.
User-friendly interface for desktop and web platforms.
Technologies Used
Programming Language: Python
Libraries and Frameworks:
Pandas
NumPy
Scikit-learn
Tkinter
Streamlit
Win32com (for speech synthesis)
Machine Learning Algorithm: Multinomial Naive Bayes
NLP Techniques: Text preprocessing, Bag-of-Words
System Requirements
Hardware Requirements
Processor: Intel i3 or higher
RAM: 4GB or higher
Storage: 500MB free space
Software Requirements
Python 3.8 or higher
Required libraries (install via requirements.txt)
Setup Instructions
Clone the Repository:

bash
Copy code
git clone <repository_link>  
cd spam-email-classification  
Install Dependencies:

bash
Copy code
pip install -r requirements.txt  
Run the Desktop Application:

bash
Copy code
python desktop_app.py  
Run the Web Application:

bash
Copy code
streamlit run web_app.py  
Usage
Enter an email message into the input field.
Click the "Classify" button.
View the result:
"Spam Email" for spam.
"Not Spam Email" for ham.
Project Structure
plaintext
Copy code
spam-email-classification/  
│  
├── data/  
│   └── spam.csv                  # Dataset  
├── models/  
│   ├── spam.pkl                  # Trained Model  
│   ├── vectorizer.pkl            # Vectorizer  
├── desktop_app.py                # Tkinter Application  
├── web_app.py                    # Streamlit Application  
├── requirements.txt              # Dependencies  
└── README.md                     # Project Documentation  
Snapshots
Desktop Application:

Web Application:

Future Enhancements
Incorporate advanced algorithms like Random Forest or Deep Learning models.
Extend the system to classify multilingual spam emails.
Integrate with email clients for real-time spam detection.
