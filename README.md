# Final project IBM Data Science Capstone: Loan Classification

With the jupyter notebook I was able to strengthen the learnings of the modules
presented in the IBM Data Science coursera.

The notebook is about a classification task of loan data. Through the course I
learned to:

* Explorative data analysis
    - Scrape data (CSV) from the web (here with wget)
    - Extract, transform and load (ETL) the data with pandas
    - Visualizing the dataframe with seaborn (matplotlib is robust but boring)

* Preparation for the classification task:
    - Feature binarization (converting a variable/column to 0, 1)
    - Feature encoding (one hot -> binary or likelihood -> [0, 1])
    - Feature selection: Loan Status (PAIDOFF or COLLECTION)
    - Data Normalization (zero (0) mean, unit (1) variance)

* Learning classification algorithms and choosing the one with the best accuracy:
    - Split Learning and Test data set
    - Learning of:
        - K nearest neighbors (KNN)
        - Decision Tree (DT)
        - Support Vector Machine (SVM)
        - Logistic Regression (LR)
    - Evaluation over test set: ⭐ SVM ⭐

## Outlook
- Training other classification algorithms:
- Deep Learning
