# 📧 Spam Email Classifier (Machine Learning)

Machine learning project to classify SMS messages as **spam** or **non-spam (ham)**.

## Problem Type
Binary Classification

## Dataset
SMS Spam Collection Dataset

## Tech Stack
- Python
- pandas
- NumPy
- scikit-learn
- TF-IDF Vectorization
- Naive Bayes

## Approach
- Text preprocessing
- TF-IDF feature extraction
- Naive Bayes classification
- Model evaluation using accuracy and confusion matrix

## Results

- The TF-IDF + Naive Bayes model achieved an accuracy of **~97%** on the test set.
- The classifier showed strong precision and recall, indicating balanced performance across spam and non-spam classes.
- Model performance was evaluated using a classification report and confusion matrix.
- Results demonstrate that classical NLP techniques can be highly effective for spam detection.


## How to Run
```bash
pip install -r requirements.txt
jupyter notebook
