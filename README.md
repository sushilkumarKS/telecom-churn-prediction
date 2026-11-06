

\# Telecom Customer Churn Prediction



\## Project Overview



Customer churn is a major challenge for telecommunications companies. This project uses machine learning to identify customers who are likely to discontinue their services.



The objective is to analyze customer data, build classification models, evaluate their performance, and understand the factors influencing customer churn.



\## Dataset



\- \*\*Source:\*\* \[Telco Customer Churn Dataset](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)

\- \*\*Records:\*\* 7,043 customer records in the original dataset.

\- \*\*Target Variable:\*\* Churn



The raw dataset is not included in this repository. Please download it from the source and place it inside the `data/` directory.



\## Project Structure



```text

telecom-churn-prediction/

├── data/

├── notebooks/

│   └── churn\_analysis.ipynb

├── images/

├── .gitignore

├── requirements.txt

└── README.md

```



\## Technologies Used



\- Python

\- Pandas

\- NumPy

\- Scikit-learn

\- Imbalanced-learn (SMOTE)

\- SHAP

\- Matplotlib

\- Seaborn



\## Methodology



1\. Data cleaning and preprocessing

2\. Exploratory Data Analysis (EDA)

3\. Feature encoding and preparation

4\. Logistic Regression, Decision Tree, and Random Forest

5\. Handling class imbalance using SMOTE

6\. Cross-validation

7\. Model explainability using SHAP



\## Results



To be added after documenting the final model evaluation results.



\## Limitations



To be added.



\## How to Run



1\. Clone this repository.

2\. Download the dataset from the Kaggle source.

3\. Place the CSV file inside the `data/` directory.

4\. Install the dependencies:



```bash

pip install -r requirements.txt

```



5\. Open the notebook:



```bash

jupyter notebook notebooks/churn\_analysis.ipynb

```



