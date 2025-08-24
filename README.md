# fake-news-classifier

This project classifies news articles as **real** or **fake** using TF-IDF features and two machine learning models: **Naive Bayes** and **Logistic Regression**.  
It includes visualizations of top adjectives, ROC curves, and confusion matrices.

---

## Open in Google Colab
Click below to run the notebook directly in Google Colab:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](
https://colab.research.google.com/github/Veronicacarr22/fake-news-classifier/blob/main/Fake_News_Classifier_Carr2025.ipynb)

---

## Repo Structure
fake-news-classifier/
   notebooks/
     FakeNewsClassifier.ipynb <- main notebook
   data/ <- folder for input CSVs (empty in repo)
     .keep <- placeholder so folder shows up
   requirements.txt
   README.md

   # fake-news-classifier

This project classifies news articles as **real** or **fake** using TF-IDF features and two machine learning models: **Naive Bayes** and **Logistic Regression**.  
It includes visualizations of top adjectives, ROC curves, and confusion matrices.

---

## Open in Google Colab
Click below to run the notebook directly in Google Colab:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Veronicacarr22/fake-news-classifier/blob/main/notebooks/FakeNewsClassifier.ipynb)

---

## Repo Structure
fake-news-classifier/
   notebooks/
     FakeNewsClassifier.ipynb <- main notebook
   data/ <- folder for input CSVs (empty in repo)
     .keep <- placeholder so folder shows up
   requirements.txt
   README.md

---

## Data
The dataset is **not included** in this repository due to size limits.  

This project uses Kaggle’s **Fake and Real News Dataset**:  
👉 [Download here](https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset)

After downloading:
- Rename `Fake.csv` → `fake.csv`  
- Rename `True.csv` → `real.csv`  
- Place both files in the `data/` folder so the notebook can read them.

If you’re running in Colab with Google Drive, the notebook can also fall back to the author’s original Drive paths.

---

##  How to Run
1. Clone this repo **or** click the Colab badge above.  
2. Make sure the dataset files (`fake.csv`, `real.csv`) are in a `data/` folder.  
3. Run all cells to preprocess, train models, and view results.

---

##  Results
- Models: Naive Bayes, Logistic Regression  
- Metrics: Accuracy, Precision, Recall, ROC AUC  
- Visual outputs: Confusion matrices, ROC curves, adjective frequency charts  

---

## Tech Stack
- Python  
- pandas, numpy  
- scikit-learn  
- nltk  
- matplotlib, seaborn  
