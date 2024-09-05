## Wine Type Classification (Supervised Learning)

**Introduction**

This project aims to classify wines into three different categories (1, 2, or 3) based on their chemical composition. It utilizes supervised learning techniques to predict the wine type using various features such as alcohol content, malic acid, ash, and others.

**Dataset**

The dataset used in this project is the well-known Wine dataset from the UCI Machine Learning Repository (<https://archive.ics.uci.edu/ml/machine-learning-databases/wine/wine.data>). It contains information about 178 wines, including their class and the values of 13 chemical properties.
More details at the end of this page.

**Methodology**

1.  **Data Preprocessing:**

      * The dataset was loaded and explored to understand its structure and characteristics.
      * Missing values were handled by imputation.
      * Feature scaling was applied to normalize the data.

2.  **Model Selection and Training:**

      * Several supervised learning algorithms were tested, including K-Nearest Neighbors (KNN), Decision Trees, Random Forest, and Logistic Regression.
      * Hyperparameters for each algorithm were tuned using grid search.
      * The models were trained on the training dataset.

3.  **Evaluation:**

      * The trained models were evaluated on the test dataset using metrics like F1-score, accuracy, precision, and recall.
      * The confusion matrix was also plotted to visualize the model's predictions.

**Results**

The K-Nearest Neighbors (KNN) algorithm with 10 neighbors and Manhattan distance metric achieved the highest F1-score of 1.00, indicating perfect classification accuracy for all classes.

**Future Work**

Potential areas for future work include:

  * **Feature Engineering:** Exploring the creation of new features from existing ones.
  * **Model Selection:** Testing other algorithms or ensemble methods.
  * **Hyperparameter Optimization:** Using more advanced hyperparameter optimization techniques.
  * **Real-World Application:** Deploying the model in a real-world setting to assess its performance on unseen data.

**Video Demonstration**

[![Image of YouTube Video Thumbnail](https://i.ytimg.com/vi/Fg_TTFAPT84/0.jpg)](https://www.youtube.com/watch?v=Fg_TTFAPT84)
