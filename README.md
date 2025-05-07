# 📦Returns Reconciliation & Claims Audit Dashboard🔍

This project presents a comprehensive Power BI dashboard built to simulate and analyze return mismatches between suppliers and manufacturers. Using a synthetic dataset generated in Python, this dashboard visualizes late returns, quantity mismatches, claim status inconsistencies, and supplier performance metrics—enabling faster, data-driven decisions in return audits.

## 📊 Project Overview

Returns reconciliation is a critical process for businesses managing high-volume logistics and supplier contracts. This dashboard serves as a **prototype audit solution** that automates mismatch detection, return validation, and supplier risk assessment.

**Built With:**
- Python (Data Simulation & Preprocessing)
- Power BI (Data Visualization)
- Synthetic Mock Data (10,000+ records)

---

## ✨ Key Features

- ✅ **Mismatch Classification**: Flags returns based on policy violations (late returns) and quantity mismatches.
- ✅ **Supplier Performance Matrix**: Tracks supplier reliability by mismatch reason.
- ✅ **Mismatch Reason Breakdown**: Visualizes the proportion of mismatch types.
- ✅ **Time Trend Analysis**: Analyzes mismatch frequency and trends by month.
- ✅ **Claim Validation**: Cross-checks supplier claim status (Approved/Rejected) with actual audit findings.
- ✅ **Return Reason Analysis**: Reveals which reasons are most commonly linked to delays or mismatches.
- ✅ **Cost Impact Summary**: Average product cost helps link operational errors with financial implications.

---

## 📌 Why This Dashboard?

Traditional tools like spreadsheets or manual ERP exports lack:
- Real-time pattern detection
- Visual diagnostics of return policy breaches
- Drill-down insights by supplier, week, or reason

**This dashboard bridges that gap with:**
- Instant discrepancy flagging
- Actionable supplier KPIs
- Auditable logic based on defined return policy rules

---

## 📈 Key Visuals & Insights

### 🔹 Total Returns Overview (Cards)
- **Total Returns**: 10,000  
- **Matched Returns**: 1,526  
- **Mismatched Returns**: 8,474  
- **Late Returns**: 5,647  
- **Average Days Since Order**: 60.07  
- **Avg. Cost Price**: $253.54

These metrics serve as high-level KPIs to understand volume and quality of returns.

---

### 🔹 Claim Status vs Actual Mismatch
**Visual**: Bar Chart  
**Insight**: 8.5K mismatched returns vs 1.5K matched, highlighting a potential misalignment between claim approvals and actual policy breaches.

### 🔹 Mismatch Trend Over Time
**Visual**: Line Chart  
**Insight**: Return mismatches peaked in March and April before falling in May. This may indicate improved processes or seasonal patterns.

### 🔹 Average Days Since Order by Return Reason
**Visual**: Bar Chart  
**Insight**: "Expired", "Defective", and "Wrong Item" returns are delayed more than "Changed Mind", indicating potential customer-side or process delays.

### 🔹 Supplier Performance Matrix
**Visual**: Matrix Table  
**Insight**: Supplier S047 and S026 are among the highest mismatch contributors. Categories like "Late Return" and "Qty Mismatch" highlight the problem type.

### 🔹 Mismatch Reason Breakdown
**Visual**: Pie Chart  
**Insight**: "Late & Qty Mismatch" is the top issue (~37%), followed by "Qty Mismatch" (~28%). Policy enforcement and claim accuracy are areas to improve.

### 🔹 Late Returns vs Mismatch Rate
**Visual**: Scatter Plot with Trendline  
**Insight**: Strong positive correlation—weeks with more late returns show higher mismatch rates. Suggests late returns are a key driver of mismatch.

---

## 💡 Dashboard Storytelling

Through this dashboard, we aim to:
- **Quantify mismatch volume and causes**
- **Diagnose supplier-level risks**
- **Track mismatch resolution trends**
- **Support decision-making with visual evidence**

---

## 📋 Recommendations

- ⚠️ **Target high-risk suppliers** for audits or policy revisions.
- 🕒 **Reduce processing delays** for commonly late return reasons.
- 🔍 **Align internal audit logic** with external claim approvals to reduce disputes.
- 📆 **Monitor mismatch trends** to plan corrective actions proactively.

---

## 🧱 Challenges Faced

- Designing clean, informative visuals without overcrowding.
- Creating meaningful synthetic data with realistic behavior patterns.
- Balancing visual storytelling with technical accuracy.
- Ensuring calculated measures (e.g., mismatch rate) reflected true logic.

---

## 📂 Dataset Structure

Simulated in Python using Faker & NumPy:

- `mock_returns.csv`: Return records
- `mock_products.csv`: Product + return policy details
- `mock_claims.csv`: Supplier claim submissions

Merged and enriched in Python → Imported to Power BI for visuals.

---

## 📎 File Structure

- mock_returns.csv
- mock_products.csv
- mock_claims.csv
- reconciliation_enriched.csv
- Returns Dashboard.pbix
- README.md

---

## 📬 Contact

For feedback or suggestions, feel free to connect via [LinkedIn](https://www.linkedin.com/in/lasya-priya-k/) or Mail me to:[Mail](konduru.lasya@gmail.com).
