# churn-prediction
# Customer Churn Prediction Project

## Project Overview
This project aims to predict customer churn for a telecommunications company. By analyzing historical customer data, we identify key factors that drive attrition and provide a list of high-risk customers for proactive retention marketing.

## Tech Stack
* **Language:** Python 3.11
* **Libraries:** Pandas, Scikit-Learn, Matplotlib, Seaborn
* **Tools:** Jupyter Notebook, Git/GitHub

## Key Findings (Insights)
* **Main Drivers of Churn:** Month-to-month contracts and Fiber Optic internet services are the strongest indicators of potential churn.
* **Retention Factors:** Long-term (two-year) contracts and Online Security services significantly help in retaining customers.
* **Model Performance:** We benchmarked multiple models. **Logistic Regression** outperformed Random Forest with an accuracy of **82%**.

## How to Use
1. Clone this repository.
2. Install dependencies: `pip install pandas scikit-learn matplotlib`.
3. Run the `01_eda_preprocessing.ipynb` notebook to see the full analysis and model training.
4. Check `high_risk_churn_list.csv` for the prioritized list of at-risk customers.

## Results
The final output is a prioritized list of customers with their predicted churn probability, allowing the business to focus retention efforts on the most "at-risk" individuals.
