Capstone Project: Warehouse Productivity and Risk Assessment
Author
Kanchan Narsinghani

Objective
The objective of this project is to analyze warehouse data to identify key factors influencing warehouse performance and risk, and to build a predictive model that helps classify warehouses based on productivity or operational risk.

Dataset
File: Data.csv
Rows: 25,000
Columns: 24

Key Features:
Location and Capacity: Location_type, WH_capacity_size, zone, WH_regional_zone

Operational Stats: num_refill_req_l3m, transport_issue_l1y, retail_shop_num, distributor_num, dist_from_hub, workers_num

Infrastructure & Conditions: electric_supply, flood_proof, flood_impacted, storage_issue_reported_l3m, temp_reg_mach, approved_wh_govt_certificate

Performance Indicators: wh_breakdown_l3m, govt_check_l3m, product_wg_ton

Notebook Overview
Notebook: Capstone_Kanchan_Narsinghani.ipynb

Key Components:
Univariate Analysis: Exploration of individual features, categorized into categorical and numerical variables.

Data Cleaning: Handling of missing values, especially in workers_num, wh_est_year, and approved_wh_govt_certificate.

Feature Engineering: Potential transformation or encoding of categorical features for modeling.

Model Building (implied): Preparation for supervised machine learning to predict warehouse productivity or classify risk.

Insights and Goals
the notebook aims to:

Understand relationships between infrastructure, environment, and warehouse output.

Identify risk factors (e.g., floods, transport issues, infrastructure deficits).

Prepare the data for classification or regression modeling (e.g., predicting tonnage or operational success/failure).

How to Use
Open the notebook: Capstone_Kanchan_Narsinghani.ipynb

Install the necessary Python packages:

bash
Copy
Edit
pip install pandas numpy matplotlib seaborn scikit-learn
Run all cells to perform EDA, clean data, and proceed with modeling.

Future Work
Complete bivariate and multivariate analysis.

Build classification or regression models.

Evaluate models using metrics such as accuracy, F1 score, or RMSE.

