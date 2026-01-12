# bank-loan-analysis
# 🏦 Bank Loan Data Analytics Dashboard (Excel)

## 📌 Project Overview

This project presents an **end-to-end Bank Loan Data Analytics Dashboard** built using **Microsoft Excel**, designed to convert raw loan data into **meaningful business and risk insights**.

The dashboard enables stakeholders to analyze:

* Loan disbursement performance
* Portfolio risk (default & delinquency)
* Product and geographic exposure
* Overall loan portfolio health

## 🛠 Tools & Technologies Used

* **Microsoft Excel**
* **Power Query** – Data cleaning & feature engineering
* **Power Pivot** – Data modeling
* **DAX** – Measures & KPIs
* **Pivot Tables & Pivot Charts**
* **Excel Slicers**
* **Filled Map Charts**

## 📂 Dataset Description

The dataset contains **loan-level banking information**, including:

* Account and client details
* Loan disbursement details
* Loan amount, interest, and collection
* Loan status indicators
* Product, grade, and maturity details
* Geographic information (State, Branch)

## 🔄 Data Cleaning & Feature Engineering (Power Query)

Data preparation was carried out in **Power Query**, focusing on **data completeness and risk analytics readiness**.

### 1️⃣ Duplicate & Data Quality Checks

* Verified uniqueness of **Account IDs**
* Checked for missing and inconsistent values
* Ensured reliable records for analysis
  
### 2️⃣ Handling Missing Values

Missing values were handled carefully to preserve data integrity:

* **Borrower Age (`Age_T`)**

  * Blank values replaced with the **median age**
  * Prevented bias and distortion in age-related analysis

* **Disbursement Officer (`Disb By`)**

  * Blank values replaced with **"UNKNOWN"**
  * Ensured complete officer-wise and operational analysis
    
### 3️⃣ Risk & Status Feature Creation

To support risk analysis and KPI calculations, the following **derived columns** were created:

* **Account Status**

  * Represents the current state of each loan account
  * Used for status-wise portfolio monitoring

* **Delinquent Flag**

  * Binary indicator identifying delinquent loans
  * Used directly in delinquent loan rate calculations

* **Default Flag**

  * Binary indicator identifying defaulted loans
  * Used in default rate KPIs and risk segmentation

These flags simplify complex logic and improve **clarity, performance, and explainability** of the data model.

### 4️⃣ Business-Oriented Data Modeling

* Risk flags were positioned **alongside their corresponding KPIs**
* Improved:

  * Measure readability
  * Dashboard transparency
  * Stakeholder understanding

✔ This approach emphasizes **business relevance over unnecessary transformations**.

## 🧠 Data Modeling & DAX Calculations

* Built relationships using **Power Pivot**
* Created DAX measures to compute:

  * Total Loans
  * Total Loan Amount
  * Total Collection
  * Total Interest
  * Default Loan Rate
  * Delinquent Loan Rate

## 📊 Key Performance Indicators (KPIs)

The dashboard highlights:

* Total Loans Issued
* Total Loan Amount Disbursed
* Total Interest Earned
* Total Collection
* Default Loan Rate
* Delinquent Loan Rate
* Unverified Loan Percentage

## 📈 Visualizations

Interactive visuals include:

* **Loan Disbursement Trend** – Line Chart
* **State-wise Loan Distribution** – Filled Map
* **Product-wise Loan Analysis** – Bar Chart
* **Loan Status Distribution** – Donut Chart
* **Grade-wise Loan Distribution** – Horizontal Bar Chart
* **Maturity-wise Loan Split** – Treemap

## 🎛 Interactive Features

* Slicers for:

  * Year
  * Month
  * Loan Purpose

* All KPIs and charts update dynamically based on selections

## 💡 Business Insights & Recommendations

### 1️⃣ Loan Disbursement Trends

Disbursement patterns show **seasonal fluctuations**, indicating predictable demand cycles.

**Recommendation:**

* Align campaigns with high-demand periods
* Optimize operational readiness

---

### 2️⃣ Product & Portfolio Concentration

Certain loan products contribute a major share of total loan value.

**Recommendation:**

* Continue promoting strong products
* Reduce concentration risk through diversification

---

### 3️⃣ Default & Delinquency Risk

Specific segments exhibit higher default and delinquency exposure.

**Recommendation:**

* Apply targeted risk controls
* Strengthen post-disbursement monitoring

---

### 4️⃣ Geographic Exposure

Loan exposure is concentrated in select states.

**Recommendation:**

* Expand cautiously into underrepresented regions
* Balance geographic risk

## 📁 Project Files

Due to GitHub file size limitations, the **Excel dashboard file and screenshots** are hosted externally.

📎 **Project Files & Screenshots**
👉 *https://drive.google.com/drive/folders/1B3nA9ib_yVbSkk26YBR3iA0va4wPCmJe?usp=sharing*

## 👤 Author

**Apeksha Sonawane**
Aspiring Data Analyst | Excel | SQL | Power BI | Tableau

## ⭐ Support This Project

If you found this project useful, please **⭐ star the repository** — it helps showcase my work to recruiters.
