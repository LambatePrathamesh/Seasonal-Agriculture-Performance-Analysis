Seasonal Agriculture Performance Analysis 🌾📊

A Data Analytics project developed as part of the VOIS AICTE Batch 1
2026--2027 Major Project. The project analyzes 4,000 agricultural
records across Kharif, Rabi, and Zaid seasons to identify seasonal
patterns, crop performance, environmental relationships, resource usage,
and economic outcomes.

📌 Project Overview

Agricultural performance is influenced by seasonal differences in
environmental conditions, farming practices, resource availability, and
market conditions. Raw data alone does not clearly explain how
performance differs between seasons.

This project analyzes agricultural data to identify:

Seasonal differences in agricultural performance

Important trends and patterns

Relationships between environmental/resource conditions and outcomes

Crop-level and regional variation

Unusual or unexpected patterns

🎯 Objectives

Analyze agricultural performance across Kharif, Rabi, and Zaid
seasons.

Clean and prepare the dataset for analysis.

Identify seasonal trends, patterns, and relationships.

Compare crop, regional, and irrigation performance.

Study environmental and resource factors related to agricultural
outcomes.

Analyze revenue, cost, and profit across seasons and crops.

Apply statistical analysis and visualization techniques.

Generate evidence-based conclusions and recommendations.

📂 Dataset

The project uses the Seasonal Agriculture Performance Dataset
containing 4,000 records and 28 columns.

Major Feature Categories

Category                            Examples

Identification                      Farm ID, State, District

Crop & Season                       Crop, Season

Farm Details                        Farm Area

Environment                         Rainfall, Temperature, Humidity,
Sunlight, Soil pH, Soil Moisture

Resources                           Nitrogen, Phosphorus, Potassium,
Fertilizer, Pesticide

Farming Practices                   Irrigation Method, Seed Quality

Production                          Yield, Production

Economics                           Market Price, Total Cost, Revenue,
Profit

Water                               Water Used, Water Efficiency

Risk                                Disease/Pest Risk

🧹 Data Cleaning & Preparation

The notebook performs:

Dataset structure and data-type inspection

Missing-value assessment

Duplicate-record checking

Categorical-value consistency checking

Missing-value treatment

Yield validation and reconstruction where required

Feature engineering

Preparation of analysis-ready data

📊 Exploratory Data Analysis

Seasonal Analysis

Average yield by season

Average production by season

Average revenue by season

Average profit by season

Seasonal profitability rates

Environmental Analysis

Rainfall

Average temperature

Humidity

Sunlight hours

Soil moisture

Disease/pest risk

Resource Analysis

Irrigation methods

Water usage

Water efficiency

Fertilizer and pesticide usage

Crop & Regional Analysis

Crop performance by season

State and district comparisons

Crop × season performance

State × season performance

Irrigation method comparisons

📈 Statistical Analysis

The project uses:

Spearman Correlation -- to examine relationships between
numerical variables.

Kruskal--Wallis Test -- to compare distributions across seasons.

Mann--Whitney U Test -- for pairwise seasonal comparisons.

Bonferroni Correction -- to control multiple-comparison errors.

IQR-based Outlier Analysis -- to identify unusual observations.

Random Forest Feature Importance -- optional predictive analysis
for yield.

🔍 Key Findings

Based on the analyzed dataset:

Kharif has the highest average yield at approximately 5.63
tonnes/hectare.

Kharif records the highest average profit of approximately
₹178,915.

Zaid has the lowest average profit, with an average loss of
approximately ₹24,805.

Kharif has the highest average water efficiency at approximately
5.89 tonnes/1000 m³.

Kharif has the highest average disease/pest risk at approximately
54.47%.

Seasonal profitability rates are approximately 57.8% for Kharif,
48.9% for Rabi, and 35.5% for Zaid.

Environmental conditions vary considerably between seasons,
especially rainfall, temperature, humidity, and soil moisture.

Crop performance and profitability vary across seasons and crop
categories.

🛠️ Technologies Used

Python

Pandas

NumPy

Matplotlib

Seaborn

SciPy

Scikit-learn

Google Colab / Jupyter Notebook

🚀 How to Run

Google Colab

Open the .ipynb notebook in Google Colab.

Upload seasonal_agriculture_performance_dataset.csv.

Run the notebook cells sequentially.

Review the generated tables, charts, statistical results, and
conclusions.

Install dependencies:

pip install pandas numpy matplotlib seaborn scipy scikit-learn openpyxl

Open the notebook:

jupyter notebook

Then run:

Seasonal_Agriculture_Performance_Analysis_VOIS_Major_Project.ipynb

📌 Project Workflow

Raw Dataset
     ↓
Data Understanding
     ↓
Data Quality Assessment
     ↓
Data Cleaning & Preparation
     ↓
Feature Engineering
     ↓
Exploratory Data Analysis
     ↓
Seasonal & Crop Analysis
     ↓
Environmental & Resource Analysis
     ↓
Economic Analysis
     ↓
Correlation & Statistical Testing
     ↓
Feature Importance Analysis
     ↓
Key Findings
     ↓
Conclusions & Recommendations

💡 Recommendations

The analysis can support:

Season-specific agricultural planning

Better crop selection and resource allocation

Improved irrigation planning

Identification of profitable crop-season combinations

Monitoring of environmental and disease/pest risks

Evidence-based agricultural decision-making

🔮 Future Scope

Crop yield prediction

Crop recommendation systems

Profit prediction

Smart irrigation planning

Weather-based agricultural forecasting

Disease and pest risk prediction

Power BI interactive dashboards

GIS-based regional analysis

Multi-year agricultural trend analysis

Real-time agricultural data integration

👨‍💻 Author

Prathamesh Sanjay Lambate
Course: VOIS AICTE Data Analytics Internship -- Major Project
Year: 2026--2027
