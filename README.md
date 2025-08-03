# Bankruptcy Prediction

Can corporate bankruptcy be predicted using financial data?

This project develops a machine learning model to classify companies based on their risk of bankruptcy, using financial ratio data. The model is trained to handle class imbalance and improve detection of rare bankruptcy cases. 

---

## About this project

This project uses financial data from **6,819 companies**, each described by **95 financial ratios**, sourced from [Kaggle](https://www.kaggle.com/datasets/fedesoriano/company-bankruptcy-prediction). The goal is to classify whether a company is likely to go bankrupt (`1`) or not (`0`), with only about 1% of companies falling into the bankrupt class.

This project includes **data cleaning**, **data manipulation**, **exploratory data analysis (EDA)**, **feature engineering**, **modelling machine learning**, and **deployment into a web app using Streamlit**.  The model is evaluated using precision, recall, and F1-score, with a focus on improving recall for the minority class to effectively identify companies at risk of bankruptcy.

📎 For a more detailed explanation, please see the PPT [Here](https://github.com/felicia2025-hue/Bankcruptcy-Prediction/blob/main/Bankcruptcy%20Prediction%20%20Presentation.pdf)

⚠️ *Due to file size, the dataset (`bankrupt.csv`) cannot be previewed on GitHub. Please **download it manually from the repository or from [Here](https://www.kaggle.com/datasets/fedesoriano/company-bankruptcy-prediction) and make sure to adjust the file path as needed** when running the code*
