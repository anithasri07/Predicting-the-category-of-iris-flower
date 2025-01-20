# Predicting-the-category-of-iris-flower
Predicts the category of Iris flowers (Setosa, Versicolor, Virginica) using multiclass logistic regression. The project involves dataset splitting, model training, evaluation, and a visualized confusion matrix.

# Predicting the Category of Iris Flower

## Description:
This project predicts the category of an Iris flower (Setosa, Versicolor, or Virginica) based on its sepal and petal measurements using multiclass logistic regression. The scikit-learn library is used for dataset loading, model training, and evaluation.

---

## Steps:
1. **Load the Dataset:** The Iris dataset is loaded using the `load_iris()` function from scikit-learn.
2. **Data Splitting:** The dataset is split into training (80%) and testing (20%) sets.
3. **Model Training:** A logistic regression model is trained using the training set.
4. **Model Evaluation:** The accuracy, classification report, and confusion matrix are generated to evaluate the model's performance.
5. **Visualization:** The confusion matrix is visualized using a heatmap for better interpretability.

---

## Requirements:
- Python 3.7+
- Libraries: scikit-learn, pandas, matplotlib, seaborn

### Installation:
Run the following commands to install the required libraries:
```bash
pip install scikit-learn pandas matplotlib seaborn
```

---

## Output:
1. **Accuracy:** The percentage of correctly classified instances.
2. **Confusion Matrix:** A heatmap showing the distribution of predictions versus actual labels.

---
