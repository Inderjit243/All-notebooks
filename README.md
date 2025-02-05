# SpaceX Falcon 9 Landing Success Prediction

## 🚀 Project Overview
This project aims to predict the success of Falcon 9 first-stage landings using historical SpaceX launch data. By leveraging exploratory data analysis (EDA), SQL queries, interactive visualizations, and machine learning models, we uncover key factors influencing landing outcomes.

## 📊 Key Insights
- **Impact of Flight Experience:** Higher flight numbers correlate with increased landing success, showing SpaceX's technological advancements over time.
- **Payload Mass Influence:** Lighter payloads generally have higher success rates, but SpaceX has improved outcomes even with heavier payloads.
- **Launch Site Performance:** Sites like **CCAFS LC-40** show a higher concentration of successful landings, suggesting operational efficiency.
- **Orbit Type and Success Rate:** Missions to LEO have higher success rates compared to GTO, likely due to less demanding mission profiles.
- **Trends Over Time:** Consistent increase in success rates since 2013, reflecting SpaceX's continuous process improvements.
- **Predictive Model Insights:** Decision Trees identified **flight number**, **payload mass**, and **launch site** as key predictors of success.
- **Geographical Trends:** Coastal launch sites near drone ships support more successful landings, emphasizing strategic location.

## 🗂️ Project Structure
```                 
├── notebooks/              # Jupyter notebooks for EDA and modeling
├── src/                    # Source code for data processing and ML models
├── visualizations/         # Interactive dashboards and visual outputs
└── README.md               # Project documentation
```

## ⚡ Technologies Used
- **Python** (Pandas, NumPy, Scikit-learn, Seaborn, Matplotlib)
- **SQL** for data querying
- **Folium** for interactive maps
- **Plotly Dash** for dashboards

## 📊 EDA Highlights
- SQL Queries for data patterns
- Scatter Plots: Flight Number vs. Payload Mass
- Bar Charts: Launch Site Success Rates
- Dashboards (Plotly Dash)

## 🤖 Predictive Models
- **Logistic Regression**
- **Decision Trees** *(Best Accuracy: 87.5%)*
- **SVM & KNN** *(Accuracy ~84.8%)*



