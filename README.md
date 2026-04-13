# SMS-Spam-Detection-using-NLP
This project focuses on building a machine learning model to classify SMS messages as spam or ham (not spam) using Natural Language Processing (NLP) techniques.

from pypandoc import convert_text

md_content = """# 📱 SMS Spam Detection using NLP

## 📌 Project Overview
This project builds a machine learning model to classify SMS messages as spam or ham using Natural Language Processing (NLP).

## 📂 Dataset
- File: clean_nus_sms.csv  
- Columns:
  - label → spam or ham  
  - text → message content  

## ⚙️ Methodology
1. Data preprocessing (cleaning text, handling missing values)
2. Feature extraction using TF-IDF
3. Model training using Logistic Regression
4. Evaluation using accuracy, precision, recall, and F1-score

## 📊 Results
- High accuracy in detecting spam messages
- Effective separation between spam and ham texts

## 🔍 Key Insights
- Spam messages often contain words like: free, win, call, claim  
- Spam messages tend to be longer  
- Ham messages are more conversational  

## ⚠️ Limitations
- May not detect new types of spam
- Limited understanding of context

## 🚀 Future Improvements
- Try Naive Bayes, SVM, or deep learning models
- Add n-grams and hyperparameter tuning

## 🛠️ Technologies Used
- Python
- Pandas
- Scikit-learn

## 📌 Conclusion
This project demonstrates how NLP techniques can be used to build an effective spam detection system.
"""

convert_text(md_content, 'md', format='md', outputfile='/mnt/data/README.md', extra_args=['--standalone'])

'/mnt/data/README.md'
