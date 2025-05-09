# Transaction Fraud Analysis


This project is a data analysis and visualization report built in Power BI, using a sample of the [PaySim](https://www.kaggle.com/datasets/ealaxi/paysim1) dataset. 
---

## 📂 Contents

- Power BI `.pbix` report with dashboards
- KPI calculations and analysis logic
- Dashboard screenshots

---

## 📊 Dataset Used

**Source**: [PaySim Synthetic Financial Transactions Dataset](https://www.kaggle.com/datasets/ealaxi/paysim1)  
**Size**:  6 million+  
**Attributes** include:
- `type`: Transaction type (`CASH_OUT`, `TRANSFER`, etc.)
- `amount`: Transaction value
- `isFraud`: 1 if fraudulent
- `isFlaggedFraud`: Flagged as fraud by the internal system
- `oldbalanceOrg`, `newbalanceOrig`, `oldbalanceDest`, `newbalanceDest`
- Account IDs (`nameOrig`, `nameDest`)

---

## 📈 Report Highlights 

### 🧮 Key KPIs

- ✅ **Total Transactions**: ~6M
- ✅ **Fraudulent Transactions**: 8213
- ✅ **Fraud Rate**: 0.36%
- ✅ **Total Fraud Amount**: 12.06bn 
- ✅ **% of Amount Involved in Fraud**: 1.05%

### 📊 Analytical Visuals

- Fraud distribution by **transaction type**
- Top 10 **victim accounts** by fraud amount
- Fraud transaction counts by **destination account**
- Detailed table of **transactions involved in fraud**
- Slicers for filtering by `isFraud`, `isFlaggedFraud`

---

## 🔍 Analysis Insights

- Most frauds occur via `CASH_OUT` and `TRANSFER` types.
- Fraud is concentrated in a small number of accounts.
- The average amount in fraudulent transactions is significantly higher than in legitimate ones.
- Destination accounts with high fraud counts could indicate mules or repeated fraud targets.

---


