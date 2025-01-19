# Bank Customer Churn Prediction

A machine learning project for predicting bank customer churn using a **Support Vector Machine (SVM)** model.

---

## Overview
This project aims to predict whether a bank customer is likely to churn (leave the bank). The predictions can help banks understand customer behavior and take proactive measures to retain valuable customers.

---

## Features
- Data cleaning and preprocessing for reliable insights.
- Exploratory Data Analysis (EDA) to uncover patterns in the data.
- SVM-based machine learning model for accurate predictions.
- Evaluation metrics like accuracy, precision, recall, and F1-score to measure performance.

---

## Technologies Used
- **Python**
- **Jupyter Notebook**
- Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

---

## How to Use
1. Clone this repository:
   ```bash
   git clone https://github.com/ketan0xg/bank-customer-churn-prediction.git
   ```
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Open the `Churn_Prediction.ipynb` file in Jupyter Notebook.
4. Run all the cells to process the data, train the model, and view the results.

---

## Dataset
The dataset contains customer information such as:
- Age
- Tenure
- Balance
- Number of products used
- Credit score, and more.

The original dataset is publicly available or can be replaced with any relevant customer data for testing.

---

## Results
The SVM model achieved the following metrics:
- **Accuracy**: ~90%
- **Precision**: ~88%
- **Recall**: ~85%
- **F1-score**: ~86%

These results highlight the effectiveness of SVM in predicting customer churn.

---

## Future Enhancements
- Experiment with other machine learning models like Random Forest or Gradient Boosting.
- Deploy the model using Flask or FastAPI for real-time predictions.
- Create an interactive dashboard using libraries like Streamlit or Dash.

---

## License
This project is open-source and available under the [MIT License](LICENSE).

