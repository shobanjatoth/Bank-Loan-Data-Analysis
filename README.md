# Bank-Loan-Data-Analysis



# Bank Loan Data Analysis

## 📌 Project Overview
This project provides a comprehensive, data-driven analysis of a bank's lending operations. By leveraging SQL and data visualization tools, this analysis monitors key performance indicators (KPIs), tracks MoM (Month-over-Month) growth metrics, assesses the financial health of the loan portfolio, and categorizes loans into "Good" vs. "Bad" risk profiles. 

The ultimate goal is to optimize lending strategies, mitigate financial defaults, and discover regional and demographic patterns among borrowers.

---

## 📊 Key Insights & Metrics
Based on the data analysis, here is a high-level summary of the bank's current loan portfolio performance:

### 1. Core KPIs (Key Performance Indicators)
* **Total Loan Applications:** **38.6K** *(with a Month-over-Month growth of +6.9%)*
* **Total Funded Amount:** **$435.8M** *(with a Month-over-Month growth of +13.0%)*
* **Total Received Amount:** **$473.1M** *(with a Month-over-Month growth of +15.8%)*
* **Average Interest Rate:** **12.0%**
* **Average Debt-to-Income (DTI) Ratio:** **13.3%**

### 2. Portfolio Risk Classification ("Good" vs. "Bad" Loans)
The bank maintains a healthy overall portfolio with **86.2%** of issued loans classified as "Good Loans".

| Category | Applications | Funded Amount | Received Amount | Portfolio % |
| :--- | :---: | :---: | :---: | :---: |
| **Good Loans** (Fully Paid & Current) | 33.2K | $370.2M | $435.8M | **86.2%** |
| **Bad Loans** (Charged Off) | 5.3K | $65.5M | $37.3M | **13.8%** |

### 3. Loan Status Breakdown
| Loan Status | Total Applications | Total Funded Amount | Total Amount Received | Avg Interest Rate | Avg DTI |
| :--- | :---: | :---: | :---: | :---: | :---: |
| **Fully Paid** | 32,145 | $351,358,350 | $411,586,256 | 11.64% | 13.17% |
| **Charged Off** | 5,333 | $65,532,225 | $37,284,763 | 13.88% | 14.00% |
| **Current** | 1,098 | $18,866,500 | $2,41,99,914 | 15.10% | 14.72% |
| **Grand Total** | **38,576** | **$435,757,075** | **$473,070,933** | **12.05%** | **13.33%** |

---

## 📈 Visualizations & Key Takeaways
* **Term Analysis:** Shorter-term loans (**36 months**) make up the majority of the portfolio at **62.66% ($273.04M)**, compared to **37.34% ($162.72M)** for long-term (**60 months**) loans.
* **Primary Loan Purpose:** **Debt Consolidation** is by far the leading reason borrowers seek funding ($0.23bn), followed closely by credit card refinancing ($0.06bn).
* **Demographics:** Borrowers with **10+ years** of employment represent the largest funded segment.
* **Home Ownership:** The highest funded amounts belong to borrowers with a **Mortgage** ($219.33M) or who **Rent** ($185.77M).

---

## 📁 Repository Structure
```text
├── 1. Overview/             # High-level introductory metrics and project context
├── 2. Problem Statement/    # Detailed business problems and analytical goals
├── 3. Dataset/              # Raw/Cleaned CSV/Excel bank loan data files
├── 4. SQL Data Analysis/     # SQL scripts containing KPI queries and data manipulations
├── 5. Dashboard/            # Interactive Power BI / Tableau visualization files
└── README.md                # Project documentation (This file)
