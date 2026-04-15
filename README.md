# Food Company Funnel Analysis 

🎯 Objective
Evaluate the effectiveness of new traffic sources for a mobile application by analyzing the conversion funnel and conducting A/A/B testing. The company needed to determine whether the new traffic sources (Group 248) generate higher conversion rates compared to traditional sources (Groups 246 and 247).

## 📊 Technologies used
Python | Pandas | SQL | NumPySciPy | Matplotlib | Seaborn | Plotly | Statistical Analysis | Statsmodels

### 🧩 Dataset structure
Each log entry represents a user action or an event '/datasets/logs_exp_us.csv'.

* EventName: Name of the event.
* DeviceIDHash: Unique user identifier.
* EventTimestamp: Time of the event.
* ExpId: Experiment number. 246 and 247 are the control groups, and 248 is the test group.

### 📎 Process
Specific Objectives:

Analyze the user conversion funnel from the main screen to successful payment
Validate the correct implementation of the experiment using A/A testing
Statistically compare conversion rates across experimental groups
Provide recommendations based on statistical evidence

### 🔬 Process and Methodology
1. Data Preparation and Cleaning
2. Conversion Funnel Analysis
3. Experimental Validation (A/A Test)
4. Experimental Analysis (A/B Testing)

🚀 Insights
📈 Results Found
Overall Conversion Funnel:

* Step 1 (MainScreenAppear): 7,436 users (100% retention)
* Step 2 (OffersScreenAppear): 4,612 users (62.0% conversion, 62.0% retention)
* Step 3 (CartScreenAppear): 3,749 users (81.3% conversion, 50.4% retention)
* Step 4 (PaymentScreenSuccessful): 3,547 users (94.6% conversion, 47.7% final retention)

## ❗Critical Point Identified:
The highest drop-off occurs between MainScreenAppear and OffersScreenAppear, where 38% of users are lost.
