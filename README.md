# Influencer Campaign Effectiveness Modeling (Data-First Approach)

## Objective
Quantify the drivers of product_sales from influencer campaigns using statistical modeling and machine learning.

## Dataset
Campaign-level influencer marketing dataset (~15,000 rows)

## Project Structure
- data/raw → Original Kaggle dataset
- data/processed → Cleaned data
- notebooks → EDA, Feature Engineering, Modeling
- src → Reusable functions
- reports → Executive summary PDF

## Methodology
1. Feature Engineering (engagement_rate, sales_per_day)
2. Linear Regression (baseline model)
3. XGBoost (non-linear modeling)
4. SHAP (model explainability)

## Business Questions
- Which platform drives highest sales efficiency?
- Does engagement translate to incremental sales?
- Do longer campaigns improve ROI?
