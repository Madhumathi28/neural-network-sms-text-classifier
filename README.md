# 📱 Neural Network SMS Text Classifier

This project is part of the FreeCodeCamp Machine Learning with Python Certification.

It classifies SMS messages as **"ham"** (normal messages) or **"spam"** (advertisements) using a **Neural Network**.

## Features
- Uses the **SMS Spam Collection dataset**.
- Preprocesses text data and converts it into numeric form using tokenization.
- Builds a Neural Network model for classification.
- Implements `predict_message(message)` function that returns:
  - Probability of ham/spam (0 to 1)
  - Label "ham" or "spam"
- Evaluates the model on test data for accuracy.

## How to Run
1. Open `sms_classifier.ipynb` in **Google Colab**.  
2. Run all cells sequentially.  
3. Use `predict_message("your message here")` to classify new messages.  

## Project Structure

```
neural-network-sms-classifier/
│
├── README.md
└── sms_classifier.ipynb
```

## Technologies Used
- Python  
- Pandas  
- NumPy  
- TensorFlow / Keras  
- scikit-learn  
- Google Colab  
