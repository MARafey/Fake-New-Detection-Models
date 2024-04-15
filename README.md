# Fake New Detection Models

This trained models for Fake news detection and their code that were utilized to train them.

The Pre-processing can be explained using this flow chart.

### Flow Diagram

![Flow Chart](https://github.com/MARafey/Fake-New-Detection-Models/assets/115175167/01522109-b0b4-4a7d-ad8c-693bed6e82fe)

### Techinques

The techinque used include: 
1. Logistic Regression
2. LSTM
3. Binary LSTM
4. XGB
5. Decision Tree
6. SVM
7. Naive Baye

### Comparison Table

| No | Technique         | Truth | Fake | Execution Time |
|----|-------------------|-------|------|----------------|
| 1  | Logistic Regression | 65   | 27   | 38.8880s      |
| 2  | Xgb               | 100   | 2    | 7.147s         |
| 3  | Binary LSTM       | 12    | 97   | 33.02s         |
| 4  | LSTM              | 0     | 5    | 24.05s         |
| 5  | Decision Tree     | 100   | 4    | 0.5432s        |
| 6  | SVM               | 16    | 64   | 2.544s         |
| 7  | Naive Bayesian    | 5     | 40   | 0.57s          |

### Reference:
1. https://github.com/nishitpatel01/Fake_News_Detection
2. https://github.com/FavioVazquez/fake-news/blob
3. https://github.com/gowrivinod/Fake-news-detection
4. https://github.com/AS-26/Fake-News-Detection-using-NLP-and-ML/tree/main
5. https://github.com/safe-graph/GNN-FakeNews
