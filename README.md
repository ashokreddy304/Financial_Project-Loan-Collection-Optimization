# Loan Collection Calls Optimization  

## 📌 Project Overview  
This project applies **statistical analysis and machine learning techniques** to optimize loan collection strategies. Using synthetic datasets, we explore payment behaviors, compare recovery channels, and analyze the effectiveness of collection calls. The goal is to provide **data-driven recommendations** that improve recovery rates and reduce operational costs.  

---

## 📂 Datasets Used  
1. **synthetic_payu_sample_2000.csv**  
   - Transaction data (timestamp, method, amount, status, settlement time, etc.)  

2. **Collection data.csv**  
   - Loan recovery amounts by channel (Digital vs Manual)  

3. **Dailer Data.csv**  
   - Call attempts, payment status, and recovery outcomes  

---

## 🛠️ Tools & Libraries  
- Python (Pandas, NumPy, Matplotlib, SciPy, Statsmodels)  
- Statistical Tests:  
  - **t-test** (mean comparisons)  
  - **Chi-Square test** (independence check)  
  - **ANOVA** (group mean differences)  
  - **Logistic Regression** (probability modeling)  

---

## 🔍 Key Analyses  

### 1. UPI vs Card Spending Behavior  
- **Result**: Card users spend ~44% more per transaction than UPI users.  
- **Insight**: Promote card payments with rewards/EMI offers; design campaigns to increase UPI ticket size.  

---

### 2. Loan Recovery – Digital vs Manual Channels  
- **Result**: Digital mean recovery = ₹8,291 vs Manual = ₹7,061 (~17% higher).  
- **Insight**: Encourage digital repayments, reduce costly manual collections, incentivize UPI/NetBanking/Auto-debit.  

---

### 3. Calls vs Recovery Rates  
- **Chi-Square Test**: More calls significantly improve recovery probability.  
- **ANOVA**: Recovery amounts differ by number of calls.  
- **Logistic Regression**: Diminishing returns after ~6–7 calls.  
- **Insight**: Optimal strategy = cap calls at 6–7 per customer to maximize efficiency without overburdening resources.  

---

## 📊 Business Recommendations  
1. **Promote Card Payments** – higher spend per transaction.  
2. **Push Digital Repayments** – higher recovery amounts, lower cost.  
3. **Optimize Call Strategy** – up to 6–7 calls per customer; avoid diminishing returns.  
4. **Segment Customers** – tailor campaigns for UPI vs Card users, Digital vs Manual payers.  

---
