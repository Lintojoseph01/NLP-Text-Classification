# **Emotion Classification in Text Samples**  

## **Project Overview**  
This project focuses on **classifying emotions in text samples** using machine learning techniques. The goal was to develop models that accurately identify emotions from text and compare their performance using **accuracy** and **F1-score**.  

## **Key Components**  

### **1. Data Loading & Preprocessing**  
- **Text Cleaning**: Removed special characters, punctuation, and converted text to lowercase.  
- **Tokenization**: Split text into individual words.  
- **Stopword Removal**: Eliminated common words that do not contribute to classification.  

These preprocessing steps helped improve model performance by reducing noise and standardizing input data.  

### **2. Feature Extraction**  
Used **TF-IDF Vectorizer** (or **CountVectorizer**) to convert text into numerical features. This transformed each document into **term frequency** or **TF-IDF** values, which were used as inputs for machine learning models.  

### **3. Model Development**  
Trained and evaluated the following models:  
✅ **Naïve Bayes** – A probabilistic classifier well-suited for text classification tasks.  
✅ **Support Vector Machine (SVM)** – A powerful classifier effective with high-dimensional text features.  

### **4. Model Comparison**  
Evaluated models using **accuracy** and **F1-score**, comparing their effectiveness in emotion classification.  

## **Results**  
| Model | Accuracy |  
|--------|----------|  
| Naïve Bayes | 90% |  
| SVM | 92% |  

## **Conclusion**  
The project successfully implemented and compared two machine learning models for **emotion classification** in text. Based on evaluation metrics, **SVM** outperformed Naïve Bayes in accuracy.  

## **Project Links**  
📌 **Colab Notebook**: [Open in Colab](https://colab.research.google.com/drive/1vAt9wVo9TQkB2wYt82brlzFs6r8SSYvx?usp=sharing)  
📌 **PDF Report**: [View PDF](https://drive.google.com/file/d/19YZzWxjCD8x2aKymqor9Cc3O42cZsXMH/view?usp=drive_link)  
