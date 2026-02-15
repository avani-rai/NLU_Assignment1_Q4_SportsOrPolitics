
# Sports vs Politics News Classifier

This project builds a machine learning based text classification system to classify news articles into two categories: **Sport** and **Politics**. The dataset used is the BBC News Classification dataset from Kaggle, from which only sport and politics articles were selected. Text documents were represented using **TF-IDF vectorization with unigrams and bigrams** to capture important keywords and phrases.

Three machine learning models were trained and compared: **Multinomial Naive Bayes, Logistic Regression, and Support Vector Machine (SVM)**. The results showed excellent performance, with Naive Bayes and SVM achieving the highest accuracy of **0.9946**, demonstrating that classical ML techniques can be highly effective for topic-based news classification.

For detailed knowledge, check out the report present in this repo named: B22CS094_prob4.pdf
The data that is used for this is in the file: bbc_data.csv
And all the code files are present in sports_vs_politics.py


