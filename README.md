# 🏦 Banking Risk & Customer Analysis

This repository contains a comprehensive data analysis project focused on risk analytics in the banking sector. The primary objective is to leverage customer data to inform lending decisions, thereby minimizing financial risk. The project involves data cleaning, feature engineering, and the creation of an interactive dashboard to visualize key metrics.

- 📝 **Python Notebooks** for data processing and analysis.
- 📊 **Interactive Dashboard** for visual storytelling and insights.
- 📄 **Project Report** detailing the methodology and findings.

## 📁 Repository Structure
```
├── 📂 data/
│   └── banking_data.csv
├── 📂 notebooks/
│   └── banking_analysis.ipynb
├── 📂 power_bi/
│   ├── banking_dashboard.pbix
│   └── dashboard_screenshot.png
└── 📄 README.md
```

## 🛠️ Tools Used
- **Excel**: Initial data exploration and validation.
- **Python (Google Colab)**: Data cleaning, transformation, and analysis.
- **Power BI**: KPI creation (using DAX) and interactive dashboard development.

## 📈 Key Insights & Recommendations

The analysis focused on creating a 360-degree view of bank clients to assess loan risk and identify patterns in customer behavior.

### 1️⃣ Feature Engineering for Deeper Insights
To better segment and understand customers, several new features were created using DAX in Power BI:
- **Engagement Timeframe**: Categorized clients based on their tenure with the bank (`<5 Years`, `5-10 Years`, etc.) to analyze loyalty and long-term value.
- **Income Band**: Segmented clients into `Low`, `Mid`, and `High` income brackets to assess financial stability.
- **Processing Fees**: Calculated applicable fees based on the fee structure, adding a layer to revenue analysis.

### 2️⃣ Key Performance Indicators (KPIs) for Risk Assessment
A set of KPIs was established to provide a quick overview of the bank's portfolio and individual client profiles:
- **Total Clients**: To measure the overall customer base.
- **Total Loan & Deposits**: To understand the balance between lending and assets.
- **Loan & Deposit Breakdown**: Analyzed different account types (Bank Loans, Business Lending, Savings, Checking) to see where capital is concentrated.

### 3️⃣ Strategic Recommendations from Dashboard Analysis
- **Client Acquisition Strategy**: The dashboard revealed that private banks have a significantly higher number of clients. This suggests that other banks should analyze and potentially adopt the strategies of private banks to attract a larger customer base.
- **Nationality-Based Risk Exposure**: By visualizing loan distribution by nationality, the bank can identify regions with high loan concentration and assess potential geopolitical or economic risks.
- **Targeted Product Offerings**: Understanding the distribution of funds across different account types (e.g., high savings account balances vs. checking accounts) allows the bank to promote specific investment products or loan offers to the right customer segments.

## Dashboard
<a href="https://www.youtube.com/your-video-link" target="_blank">
  <img src="https://img.icons8.com/?size=100&id=3sGOUDo9nJ4k&format=png&color=000000" alt="Live Dashboard" width="50" height="50">

_[View live Dashboard](https://app.powerbi.com/groups/me/reports/790cd185-145d-433f-a6ce-be0ab8b2eb27/ReportSection53c77500ece20cb68932?experience=power-bi)_
  
Get more insights and knowledge about Banking Risk & Customer Analysis
