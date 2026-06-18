# ML Projects Portfolio — Durgesh Dubey

MS in Computer Science (ML & AI Engineering) | Ex-Railofy Data Analyst



## Project 1 — Customer Segmentation & Retention Analysis
**Tools:** Python, pandas, scikit-learn, K-Means, matplotlib, seaborn

Segmented 5,878 customers from 1M+ retail transactions using RFM analysis 
and K-Means clustering. Identified 4 segments including 4 Champion customers 
with avg spend of £436K and 1,998 At-Risk customers needing win-back campaigns.

[View Notebook](./Project1_Customer_Segmentation.ipynb)



## Project 2 — Demand Forecasting / Time Series Modeling
**Tools:** Python, pandas, Prophet, matplotlib, sklearn

Forecasted 30-day daily revenue using Facebook Prophet on 604 days of retail data.
Discovered Thursday peak pattern and November seasonal spike. MAE: £12,336 on avg daily revenue of £43,472.

[View Notebook](./Project2_Demand_Forecasting.ipynb)



## Project 3 — NLP-Based Insights from Customer Reviews
**Tools:** Python, pandas, NLTK, VADER, LDA, WordCloud, matplotlib

Analyzed 50,000 Amazon food reviews using VADER sentiment analysis (79.1% accuracy).
Extracted 5 complaint themes using LDA topic modeling — delivery issues, 
pet food quality, beverage flavor complaints.

[View Notebook](./Project3_NLP_Sentiment_Analysis.ipynb)



## Project 4 — A/B Testing & Experimentation Analysis
**Tools:** Python, pandas, scipy, statsmodels, matplotlib

Analyzed a 294,478-user e-commerce A/B test using two-proportion z-test.
Found new landing page had NO statistically significant uplift (p=0.2161).
Recommended against rollout saving potential development costs.

[View Notebook](./Project4_AB_Testing.ipynb)



## Project 5 — Customer Churn Prediction & Deployment
**Tools:** Python, pandas, scikit-learn, XGBoost, Streamlit

Predicted customer churn for 7,043 telecom customers using Logistic Regression, 
Random Forest, and XGBoost. Logistic Regression performed best (AUC: 0.8306, 
Accuracy: 78.54%), outperforming both ensemble models. Deployed as a live 
interactive web app on Streamlit Cloud for real-time churn predictions.

[View Notebook](./Project5_Churn_Prediction.ipynb) | [View App Repo](https://github.com/thisisdurgeshdubey/churn-prediction-app) | [Live App](https://churn-prediction-app-dvtp4qd4escmiazbfqpqse.streamlit.app/)
