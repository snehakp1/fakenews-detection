# Fake News Detection using Machine Learning

This project applies Natural Language Processing (NLP) and Machine Learning techniques to detect fake news from real news. It involves cleaning and processing news text, extracting features, and training classification models to distinguish between true and false news articles.

## Project Files

- `fake-news-detection.ipynb`: Jupyter notebook with the full implementation.
- `dataset/`: Folder containing the dataset CSV file (not included here).
- `README.md`: Project documentation (this file).

---

##  Features

- Data preprocessing: punctuation removal, lowercase conversion, stopword removal, etc.
- Feature extraction using TF-IDF vectorizer.
- Model training using machine learning algorithms.
- Performance evaluation using metrics like accuracy and classification report.

---

##  Libraries Used

- pandas  
- numpy  
- matplotlib  
- seaborn  
- scikit-learn  
- re (regex)  
- string

---

##  Dataset Format

The dataset used for this project should be a CSV file with the following columns:

- `text` – the news article content
- `label` – the class label (`FAKE` or `REAL`)

Place your dataset in a folder named `dataset/`.

---

##  How to Run

1. Clone the repository:

```bash
git clone https://github.com/snehakp1/fake-news-detection.git

