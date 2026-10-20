# Mini-Project-1
# What drives a Telco customer's monthly bill, and do big spenders churn more?

**Live app:** https://mini-project-1-bh9nn6yupmfh2obstumxma.streamlit.app/

**Dataset:** Telco Customer Churn, https://www.kaggle.com/datasets/blastchar/telco-customer-churn?resource=download

**Target:** MonthlyCharges (predicted with a constant model and OLS with one-hot encoded InternetService)

## Faithfulness & Granularity
- Each row is one customer...
- Scope: 7,043 customer records from the IBM Telco dataset
- Strange values: 11 blank TotalCharges values, all had tenure = 0
- Duplicates: none

## Key finding
Holding tenure constant, fiber optic customers are predicted to pay about $33.60 more per month than DSL customers.

## Run locally
streamlit run app.py

https://mini-project-1-bh9nn6yupmfh2obstumxma.streamlit.app/
