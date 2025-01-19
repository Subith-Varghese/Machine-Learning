# Machine Learning

### 1. CSGO Game Project :
I implemented classification models for predicting game outcomes based on player and game-related features.

* Data Preprocessing: Cleaned and processed a dataset of 97 features, including handling missing values, duplicates, and encoding categorical features using Label Encoding.
* Feature Engineering: Applied Linear Discriminant Analysis (LDA) for feature selection and identified the top 20 features most influential in predicting game outcomes.
* Model Building & Evaluation:
  * Trained and evaluated multiple classifiers: Logistic Regression, Decision Tree, and Random Forest.
  * Achieved 85.39% accuracy with Random Forest, 80.83% with Decision Tree, and 75.86% with Logistic Regression.
* Model Optimization: Standardized features using StandardScaler and tuned models to achieve optimal performance.
* Tools & Libraries: Python, Scikit-learn, Pandas, NumPy, Matplotlib.




### 2. Project: census-income-imbalanced-classification-modeling
* Handled Imbalanced Data: Applied ADASYN (Adaptive Synthetic Sampling) to balance class distribution in the dataset, improving model performance on the minority class.
* Model Building & Evaluation: Built and evaluated several machine learning models (Logistic Regression, Decision Tree, Random Forest) to predict target variable.
 * Improved model accuracy from 83.7% (Decision Tree) to 85.4% after hyperparameter tuning.
 * Achieved a balanced precision-recall trade-off, enhancing model robustness.
* Hyperparameter Tuning: Utilized GridSearchCV to tune Decision Tree classifier, resulting in improved performance with max_depth=40, min_samples_leaf=2, and min_samples_split=100.
* Performance Metrics: Monitored and optimized for precision, recall, F1-score, and accuracy to ensure balanced model performance.
