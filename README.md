# Wine Quality Prediction Using Machine Learning

## Project Overview

This project aims to predict wine quality using Machine Learning techniques based on the chemical characteristics of wine. Various classification algorithms are implemented and compared to determine the most effective model for predicting wine quality.

The project demonstrates data preprocessing, exploratory data analysis, feature engineering, model training, evaluation, and visualization using Python data science libraries.

---

## Dataset Information

Dataset: WineQT Dataset

Total Records: 1143

Features:

- Fixed Acidity
- Volatile Acidity
- Citric Acid
- Residual Sugar
- Chlorides
- Free Sulfur Dioxide
- Total Sulfur Dioxide
- Density
- pH
- Sulphates
- Alcohol
- Quality

Target Variable:

- Quality

For classification purposes:

- Quality ≥ 7 → Good Wine (1)
- Quality < 7 → Bad Wine (0)

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Machine Learning Models

The following classification algorithms were implemented:

### Random Forest Classifier
An ensemble learning method that combines multiple decision trees to improve prediction accuracy and reduce overfitting.

### Stochastic Gradient Descent (SGD) Classifier
A linear classifier optimized using gradient descent, suitable for large datasets and fast training.

### Support Vector Classifier (SVC)
A supervised machine learning algorithm that identifies the optimal boundary between classes.

---

## Project Workflow

### 1. Data Loading
- Imported the WineQT dataset using Pandas.

### 2. Data Cleaning
- Removed unnecessary columns.
- Checked for missing values.

### 3. Exploratory Data Analysis
- Wine Quality Distribution
- Correlation Analysis
- Feature Relationships

### 4. Data Visualization
- Count Plot
- Correlation Heatmap
- Accuracy Comparison Graph
- Confusion Matrix

### 5. Feature Engineering
- Selected relevant chemical properties as input features.
- Converted wine quality scores into binary classification labels.
- Applied feature scaling using StandardScaler.

### 6. Model Training
The dataset was divided into:

- Training Data: 80%
- Testing Data: 20%

Three machine learning models were trained and evaluated.

### 7. Model Evaluation
Performance was measured using:

- Accuracy Score
- Precision
- Recall
- F1-Score
- Confusion Matrix

---

## Key Insights

- Most wine samples belong to medium quality categories.
- Alcohol content shows a strong relationship with wine quality.
- Sulphates and citric acid positively influence wine quality.
- Volatile acidity tends to negatively impact wine quality.
- Feature scaling improves the performance of distance-based algorithms such as SVC.
- Random Forest effectively captures complex relationships between wine characteristics and quality.

---

## Visualizations Included

- Wine Quality Distribution Plot
- Correlation Heatmap
- Good vs Bad Wine Distribution
- Model Accuracy Comparison
- Confusion Matrix
- Feature Importance Analysis

---

## Results

Three machine learning models were compared:

- Random Forest Classifier
- SGD Classifier
- Support Vector Classifier (SVC)

The best-performing model was selected based on classification accuracy and overall evaluation metrics.

---

## Sample Prediction

The trained model predicts whether a wine is:

- Good Quality Wine
- Bad Quality Wine

based on its chemical composition.

---

## Conclusion

This project demonstrates the application of machine learning in wine quality prediction using chemical characteristics. By comparing multiple classification algorithms, the project identifies an effective approach for predicting wine quality and provides insights into the factors that influence wine evaluation.

---

## Future Enhancements

- Hyperparameter Tuning
- Cross Validation
- XGBoost Implementation
- Deep Learning Models
- Streamlit Web Application
- Real-Time Prediction System


```

## Author

Jegadeeswari

Machine Learning Project – Wine Quality Prediction
