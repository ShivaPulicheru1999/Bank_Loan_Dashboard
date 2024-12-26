# Bank_Loan_Dashboard
Power bi Dashboard

### Technologies used
<img src="https://github.com/user-attachments/assets/afac138f-5d94-436d-afb2-1761bcfc1a23" width="100" height="50" />
<img src="https://github.com/user-attachments/assets/04726459-d460-4321-af5d-cb1c47867a66" width="100" height="50" />

## # README for Loan KPI Dashboad

## Overview
This project focuses on building a comprehensive analytics dashboard to monitor loan performance and insights. The dashboard will showcase Key Performance Indicators (KPIs), provide grid views, and display various data visualizations to assist in data-driven decision-making. Below are the key components, KPIs, and processes involved in the project.

---

## Key Performance Indicators (KPIs)
### General KPIs:
1. **Total Loan Applications:**
   - Determine the total number of loan applications submitted over a specific timeframe.
   - Track Month-to-Date (MTD) Loan Applications.

2. **Total Funded Amount:**
   - Monitor the total funds disbursed as loans.
   - Focus on the Month-to-Date (MTD) Total Funded Amount.

3. **Total Amount Received:**
   - Track total repayments collected from borrowers.
   - Review Month-to-Date (MTD) Total Amount Received.

4. **Average Interest Rate:**
   - Calculate the overall average interest rate for all loans, including Month-to-Date (MTD).

5. **Average Debt-to-Income Ratio (DTI):**
   - Assess the average Debt-to-Income Ratio (DTI) for borrowers to gauge their financial health.
   - Compute this metric for all loans, Month-to-Date (MTD).

### Good Loan vs. Bad Loan KPIs:
#### **Good Loan:**
- Good Loan Application Percentage
- Good Loan Applications
- Good Loan Funded Amount
- Good Loan Total Received Amount

#### **Bad Loan:**
- Bad Loan Application Percentage
- Bad Loan Applications
- Bad Loan Funded Amount
- Bad Loan Total Received Amount

### Loan Status Grid View:
The grid view report categorizes loans by 'Loan Status' and provides insights into:
- Total Loan Applications
- Total Funded Amount
- Total Amount Received
- Month-to-Date (MTD) Funded Amount
- Month-to-Date (MTD) Amount Received
- Average Interest Rate
- Average Debt-to-Income Ratio (DTI)

This grid view empowers users to monitor loan portfolio health and make data-driven decisions.

- Dashboard interaction<a href="https://github.com/ShivaPulicheru1999/Bank_Loan_Dashboard/blob/main/Bank%20Loan%20Sumary.pdf"> View Dashboard</a>

---

## Charts and Visualizations
1. **Monthly Trends by Issue Date (Line Chart):**
   - Identify seasonality and long-term trends in lending activities.

2. **Regional Analysis by State (Filled Map):**
   - Highlight regions with significant lending activity and assess regional disparities.

3. **Loan Term Analysis (Donut Chart):**
   - Display the distribution of loans across various term lengths.

4. **Employee Length Analysis (Bar Chart):**
   - Show lending metrics distribution among borrowers based on employment length.

5. **Loan Purpose Breakdown (Bar Chart):**
   - Provide a visual breakdown of loan metrics by loan purpose to understand borrower needs.

6. **Home Ownership Analysis (Tree Map):**
   - Offer a hierarchical view of how home ownership impacts loan applications and disbursements.

### Metrics for Visualizations:
- Total Loan Applications
- Total Funded Amount
- Total Amount Received
- Dashboard interaction<a href="https://github.com/ShivaPulicheru1999/Bank_Loan_Dashboard/blob/main/Bank%20Loan%20Overview.pdf"> View Dashboard</a>
---

## Workflow and Steps
### Data Preparation
1. **Connecting to CSV File:**
   - Import loan data from external sources (e.g., CSV files).
2. **Data Cleaning:**
   - Remove duplicates, handle missing values, and standardize formatting.
3. **Data Modeling:**
   - Establish relationships between tables for efficient querying.
4. **Data Processing:**
   - Leverage Power Query to transform and load data into Power BI.

### Technical Features
1. **Date Tables:**
   - Use date tables for time-based calculations.
2. **Time Intelligence Functions:**
   - Implement Month-to-Date (MTD), Year-to-Date (YTD), and Month-over-Month (MoM) calculations.
3. **Key DAX Functions:**
   - Date Functions
   - Text Functions
   - Filter Functions
   - CALCULATE
   - SUM/SUMX

### Dashboard Creation
1. **KPIs:**
   - Create and display key metrics using Card visuals.
2. **Charts:**
   - Design interactive charts for trend and comparative analysis.
3. **Formatting Visuals:**
   - Ensure visuals are consistent and easy to interpret.
4. **Navigation:**
   - Add buttons or bookmarks for seamless navigation within the dashboard.

---

## Repository Structure
```
Loan-KPI-Dashboard/
|-- data/
|   |-- raw_data.csv          # Raw data files
|   |-- cleaned_data.csv      # Processed data
|
|-- scripts/
|   |-- data_cleaning.pbix    # Power Query steps
|   |-- dax_functions.txt     # Common DAX functions used
|
|-- visuals/
|   |-- charts_screenshots/   # Screenshots of dashboard visuals
|
|-- README.md                 # Project overview
```

|
|-- visuals/
|   |-- charts_screenshots/   # Screenshots of dashboard visuals
|
|-- README.md                 # Project overview

