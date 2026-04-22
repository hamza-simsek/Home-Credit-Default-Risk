# Home Credit Default Risk Prediction 🏦

This project was developed to predict the default risk (repayment failure) of loan applicants using data provided by **Home Credit**. The project covers the entire data science pipeline, including data cleaning, feature engineering, machine learning modeling, and interactive reporting.

## 📂 Dataset
The dataset used in the analysis was obtained from Kaggle:
🔗 [Home Credit Default Risk - Kaggle](https://www.kaggle.com/c/home-credit-default-risk/data)

## 📊 Project Components

### 1. Data Analysis & Business Intelligence (Power BI)
An interactive dashboard was designed to examine the impact of demographic and financial variables on credit risk.
- **Key Insights:** Analysis of the inverse correlation between age and default rates, and the impact of various income segments on risk.
- **File:** `reports/Home-Credit.pbix`

### 2. Machine Learning Modeling (Python & Colab)
An end-to-end pipeline was built using Python libraries to forecast credit default risks.
- **Libraries:** Pandas, NumPy, Scikit-learn, LightGBM/XGBoost, Matplotlib, Seaborn.
- **Process:** Missing value management, outlier analysis, label/one-hot encoding, and model hyperparameter optimization.
- **File:** `notebooks/Home-Credit-Modeling.ipynb`

## 📈 Key Analysis & Insights
The visualization below illustrates the change in default rates across different age groups. Our analysis reveals that younger age groups tend to have a significantly higher risk of default.

![Default Risk Analysis](visuals/visual2.png) 

## 🛠️ Installation & Usage
To run this project locally:
1. Clone the repository: `git clone https://github.com/hamza-simsek/Home-Credit-Default-Risk.git`
2. Install requirements: `pip install -r requirements.txt`
3. Open the notebook file via Jupyter Notebook or Google Colab.

## 📄 License
This project is licensed under the [MIT License](LICENSE).
