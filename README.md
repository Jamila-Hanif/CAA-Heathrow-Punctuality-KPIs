# CAA Heathrow Punctuality KPIs + ML Prediction

*Flight Data Analysis Portfolio for Riyad Air Vision 2030*  
Analyzed UK Civil Aviation Authority 2024 data to calculate airline punctuality KPIs and predict airport delays using Machine Learning.

### Key Findings
*1. KPI Analysis*
•⁠  ⁠*Heathrow On-time Performance*: 67.3% of flights depart/arrive <15min late
•⁠  ⁠*Delay Rate*: 32.7% of flights delayed >15min 
•⁠  ⁠*Focus Airport*: London Heathrow EGLL - UK's busiest hub, directly relevant to Riyad Air ops

*2. Data Visualization*
•⁠  ⁠On-time vs Delayed distribution pie chart
•⁠  ⁠Top 10 UK airports by on-time % bar chart

*3. ML Prediction Model*
•⁠  ⁠*Model*: RandomForest Regressor
•⁠  ⁠*Target*: ⁠ Average_Delay_Minutes ⁠ per airport/month
•⁠  ⁠*Accuracy*: MAE 1.52 minutes - predictions off by ~2 min on average
•⁠  ⁠*Key Insight*: ⁠ Flights_on_time_(<15mins)_Percent ⁠ drives 86% of delay variance

<img width="2365" height="1166" alt="feature_importance_delays (1)" src="https://github.com/user-attachments/assets/c88298a6-c921-4d3b-a39b-8203a212a2ac" />


### Technical Stack
⁠ Python ⁠ ⁠ Pandas ⁠ ⁠ Matplotlib ⁠ ⁠ Scikit-learn ⁠ ⁠ RandomForest ⁠ ⁠ KPI Analysis ⁠

### Business Impact for Airlines
This analysis mirrors Riyad Air Flight Data Analyst daily work:
1.⁠ ⁠*Monitor KPIs*: Track on-time %, cancellations, total flights
2.⁠ ⁠*Identify Drivers*: 86% of delays tied to on-time % = ops teams know where to focus
3.⁠ ⁠*Forecast Disruption*: ML model predicts delay minutes for capacity planning under Vision 2030

### Dataset
UK CAA Airport Statistics 2024 - Monthly punctuality KPIs for UK airports

### How to Run
1.⁠ ⁠Open ⁠ airport_data.ipynb ⁠ in Google Colab
2.⁠ ⁠Runtime → Run all cells
3.⁠ ⁠Charts + model output generate automatically

---
Built by Jameela Hanif | Aspiring Flight Data Analyst Officer | Riyad Air Vision 2030

**Visuals**:
<img width="2100" height="2100" alt="heathrow_punctuality_pie" src="https://github.com/user-attachments/assets/1a39c12e-579f-459f-bdaa-db4794e52616" />
<img width="3300" height="2100" alt="uk_airports_ontime_chart" src="https://github.com/user-attachments/assets/db932662-241c-46d2-b3da-877cb76b51d8" />
