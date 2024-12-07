# **Spam Email Classification using NLP and Machine Learning**

## **Project Overview**
This project implements a **Spam Email Classification System** using **Natural Language Processing (NLP)** and **Machine Learning** techniques. The system is designed to classify emails as either "spam" or "ham" (not spam). It uses the **Naive Bayes** classification algorithm after extracting relevant features from the email content using **Bag-of-Words (BoW)**. 

The project includes two user interfaces:
- **Desktop Application**: Built using **Tkinter**, which provides a simple GUI for classifying emails.
- **Web Application**: Built using **Streamlit**, providing a web interface for email classification.

## **Technologies Used**
- **Programming Language**: Python
- **Libraries & Frameworks**:
  - **Pandas** for data manipulation
  - **NumPy** for numerical computations
  - **Scikit-learn** for machine learning algorithms
  - **Tkinter** for the desktop application
  - **Streamlit** for the web application
  - **win32com.client** (for text-to-speech functionality in the desktop app)
- **Machine Learning Algorithm**: **Multinomial Naive Bayes**
- **NLP Techniques**: 
  - Text Preprocessing
  - Bag-of-Words (BoW) Vectorization

## **Features**
- **Email Classification**: Classifies inputted email messages into **Spam** or **Ham**.
- **Speech Output**: Provides speech output for classification results (Desktop Application).
- **Web Interface**: A simple and intuitive web interface (Streamlit).
- **Quick Prediction**: Efficient and lightweight model that gives quick predictions.

## **Setup Instructions**

### **Step 1: Clone the Repository**
Clone this repository to your local machine using the following command:
```bash
git clone https://github.com/yourusername/spam-email-classification.git
cd spam-email-classification
