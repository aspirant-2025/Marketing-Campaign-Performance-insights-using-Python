# Marketing-Campaign-Performance-insights-using-Python
## 📌 Project Overview
In the fast-evolving landscape of digital marketing, measuring the success of campaigns across various platforms and demographics is crucial. This project analyzes a rich dataset of marketing campaigns to uncover performance trends, optimize strategies, and drive better ROI.

**Dataset Source:**  
[Marketing Campaign CSV Dataset](https://raw.githubusercontent.com/ArchanaInsights/Datasets/main/marketing_campaign.csv)

# 🧩 Problem Statement

Companies run numerous campaigns using diverse strategies and channels. The challenge lies in understanding:
- What influences conversion rates and **ROI**?
- How do **channel**, **location**, **audience**, and **language** affect performance?
- Are there **temporal or geographic patterns** we can learn from?

This analysis provides insights into such questions using Python-based data analysis and visualizations.

# 🛠 Tools & Technologies

- **Python (Pandas, NumPy)**
- **Seaborn & Matplotlib** for data visualization
- **Jupyter Notebook / Google Colab**
- **CSV dataset** for analysis

## 📋 Project Steps

### 1. Load the Dataset
- Loaded the CSV file using pandas into a DataFrame.

### 2. Descriptive Analysis
- Displayed shape, head, info, and basic statistics.
- Analyzed:
  - Unique Campaign IDs
  - Unique Locations and Customer Segments
  - Distribution of Campaign Types and Channels Used

### 3. Exploratory Data Analysis (EDA)

#### ✅ Campaign Performance
- Scatter plot: **Acquisition Cost vs ROI**
- Bar chart: Avg **Conversion Rate by Channel & Campaign Type**
- Box plot: **Engagement Score** across Campaign Types
- Bar chart: Avg **ROI by Company**
- Heatmap: Correlation between **Engagement Score** & **Conversion Rate**

#### 🎯 Customer Segmentation
- Count plot: **Target Audience** distribution
- Bar chart: **Top Customer Segments by Language**
- Box plot: **Acquisition Cost by Channel & Customer Segment**
- Bar chart: **Avg Conversion Rate by Language**

#### 📈 Channel Effectiveness
- Bar chart: **Engagement Score by Channel & Campaign Type**
- Pie chart: **Total ROI by Channel**
- Scatter plot: **Clicks vs Impressions by Channel**

#### 🕒 Time-Based Trends
- Histogram: **Campaign Duration**
- Line chart: **Conversion Rate over Time by Company**
- Line chart: **Engagement Score over Time**

#### 🌍 Geographic Insights
- Bar chart: **Top Location by Acquisition Cost**
- Bar chart: **Conversion Rate by Location & Target Audience**
- Pie chart: **ROI Distribution by Location**

## 📌 Key Insights

- Some channels (like Google Ads) consistently drive higher ROI despite higher acquisition costs.
- Campaigns in certain languages (e.g., Spanish) show stronger conversion rates for specific customer segments.
- Companies with consistent engagement tend to see higher ROI over time.
- Geographic locations influence both cost and conversion effectiveness.

## 📈 Outcome

This analysis enables data-driven decisions for optimizing future marketing campaigns, improving targeting, and allocating budgets across channels more effectively.

## 🔗 Dataset Credit

[ArchanaInsights - GitHub](https://github.com/ArchanaInsights/Datasets)

