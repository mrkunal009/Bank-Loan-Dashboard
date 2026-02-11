# Bank Loan Analysis (Power BI Dashboard)

A Power BI dashboard project to analyze bank loan performance using key lending KPIs, risk segmentation (Good vs Bad loans), and drill-down views across time, geography, and borrower attributes.

📌 Project Overview
This report helps track loan portfolio health by answering questions like:
- How many loan applications are coming in (total / MTD / MoM)?
- How much amount is funded vs received?
- How are interest rate and DTI changing over time?
- What share of loans are **Good** vs **Bad**, and where is risk concentrated?

The dashboard is designed for fast decision-making with interactive filters and detailed breakdowns.

📄 Report Pages
1) SUMMARY
High-level KPI snapshot with quick risk view:
- Total Loan Applications
- Total Funded Amount
- Total Amount Received
- Avg Interest Rate
- Avg DTI
- Good vs Bad loan split (counts + %)

2) OVERVIEW
Trend + distribution insights:
- Time-based trends (monthly)
- Comparisons across categories (example: term, grade, purpose)
- Portfolio mix visualizations (bar / area / treemap / donut)

3) DETAILS
Granular analysis for validation and deep-dives:
- Record-level / grouped table view
- KPI cards + slicers for quick filtering

📊 Key Metrics (DAX Measures)
This report includes commonly used lending KPIs such as:
- TOTAL LOAN APPLICATION
- TOTAL FUNDED AMOUNT
- TOTAL AMOUNT RECEIVED
- AVG INTEREST RATE
- AVG DTI
- MTD metrics (applications, funded, received, avg int rate, avg DTI)
- MoM metrics (applications, funded, received, avg int rate, avg DTI)
- GOOD LOAN % / BAD LOAN %
- GOOD LOAN / BAD LOAN (applications, funded amount, received amount)
  

 1. Summary Page
High-level KPI snapshot including:
- Total Loan Applications
- Total Funded Amount
- Total Amount Received
- Avg Interest Rate
- Avg DTI
- Good vs Bad Loan %

🔹 2. Overview Page
Trend & segmentation analysis:
- Monthly trend charts
- Loan distribution by state
- Term / Grade / Purpose breakdown
- Portfolio risk visualization


 🔹 3. Details Page
Granular drill-down table view:
- Individual loan records
- Filterable KPIs
- Advanced slicers

 📈 Key Metrics Implemented

- TOTAL LOAN APPLICATION
- TOTAL FUNDED AMOUNT
- TOTAL AMOUNT RECEIVED
- AVG INTEREST RATE
- AVG DTI
- MTD Metrics
- MoM Metrics
- GOOD LOAN %
- BAD LOAN %
- Risk-based segmentation KPIs

 🛠 Tools Used

- Power BI Desktop
- DAX (Time Intelligence + KPIs)
- Power Query (Data Cleaning & Transformation)

---

## 📂 Project File

- `completer.pbix`

---

## 📌 How to Run

1. Install Power BI Desktop
2. Open `completer.pbix`
3. Refresh dataset if needed
4. Interact with slicers & filters

---



🧩 Dimensions / Fields Used
The analysis uses borrower + loan attributes such as:
- State
- Term
- Purpose
- Grade / Sub-grade
- Home ownership
- Employment length
- Loan status
- Installment, interest rate, issue date, etc.

A Date table is used for time intelligence (monthly trend, MTD, MoM).

🗂 File Included
- `completer.pbix` — Power BI report file

✅ How to Use
1. Install Power BI Desktop
2. Open `completer.pbix`
3. If the dataset is linked externally, update the data source path:
   - `Home > Transform data > Data source settings`
4. Refresh:
   - `Home > Refresh`

🛠 Tools & Tech
- Microsoft Power BI Desktop
- DAX (measures for MTD/MoM, portfolio KPIs)
- Power Query (ETL, cleaning, formatting)



## 👤 Author
KUNAL KUMAR
