
# Logistic Regression - Binary Classification

## Objective
To build a binary classifier using Logistic Regression on the Breast Cancer Wisconsin dataset.

## Dataset
The dataset used is the Breast Cancer Wisconsin Dataset from Scikit-learn.

## Tools & Libraries Used
- Python
- Pandas
- Scikit-learn
- Matplotlib
- NumPy

## Workflow
1. **Data Loading:** Loaded Breast Cancer Wisconsin dataset using `sklearn.datasets`.
2. **Data Preprocessing:** Standardized features using `StandardScaler`.
3. **Model Building:** Used `LogisticRegression` from `sklearn.linear_model`.
4. **Evaluation:**
   - Confusion Matrix
   - Precision, Recall, F1-score
   - ROC-AUC Curve
5. **Visualization:** Plotted ROC Curve.

## Results
- ROC-AUC Score: 1.00
- See `roc_curve.png` for ROC visualization.
- Evaluation metrics are stored in `results.json`.

## How to Run
1. Install required libraries: `pip install -r requirements.txt`
2. Open and run the `.ipynb` file.

