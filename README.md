# 📊 Network & Allocation Optimization Models

This repository contains three applied optimization case studies developed for BAN 630 – Optimization for Analytics.

The projects demonstrate linear programming, trade-off analysis, and sensitivity modeling in real business contexts.

---

# 1️⃣ Marico – Warehouse Network Optimization

## 📌 Business Problem

Marico must decide whether to operate:

- 22 warehouses  
- 24 warehouses  

The decision affects:

- Service levels  
- Freight costs  
- Rental expenses  
- Future scalability  

---

## 🎯 Potential Objectives (Ranked)

1. Improve service levels (customer-centric priority)  
2. Optimize warehouse count  
3. Reduce freight & operational cost  
4. Balance cost and responsiveness  

---

## ✅ Final Recommendation

**24 warehouses**

### Why?

- Significant service improvement in North and South regions  
- Minimal additional cost relative to revenue impact  
- Better support for future demand growth  
- More flexibility for demand elasticity  

Net benefit outweighs incremental warehouse costs.

---

# 2️⃣ Simon’s Mall – Retail Space Allocation

## 📌 Business Problem

Simon’s Mall has 9,000 sq ft of space and must decide:

- How many stores of each type to allow  
- How to maximize rental income  

Stores pay **7.5% of annual profit as rent**.

---

## ✅ Optimal Allocation (Base Case – 9,000 sq ft)

- Jewelry: 3  
- Shoe: 2  
- Department: 2  
- Book: 1  
- Clothing: 3  

**Total Annual Rental Income: $95,250**

---

## 📈 Sensitivity Analysis

Increasing space:

- At 11,000 sq ft → Profit increases significantly  
- Beyond 11,000 sq ft → Diminishing returns  

Adding clothing stores drove the largest improvement in profitability.

Conclusion:

- 11,000 sq ft yields highest total profit
- Further expansion does not justify infrastructure cost

---

# 3️⃣ The Cubs – Budget-Constrained Player Selection

## 📌 Business Problem

The Cubs must select pitchers to:

- Maximize total victories  
- Stay within a budget  
- Respect signing constraints  

Constraints:

- Budget ≤ $55M  
- ≤ 3 right-handed pitchers  
- Cannot sign BS, RS, and DE together  

---

## ✅ Optimal Selection (Base Budget: $50M)

- RS  
- DE  
- ST  
- TS  

**Total Wins Added: 14**

---

## 📊 Budget Sensitivity

- At $50M → 14 wins  
- At $58M → 16 wins  

Extra $8M yields 2 additional victories.

Managerial Decision:

- Worth it if playoff qualification probability increases  
- Not worth it early in season without competitive urgency  

---

# 🛠 Techniques Used

- Linear Programming  
- Constraint Modeling  
- Multi-Objective Trade-Off Analysis  
- Sensitivity Analysis  
- Scenario Evaluation  

---

# 🎯 Skills Demonstrated

- Network optimization thinking  
- Service vs cost trade-off modeling  
- Space allocation optimization  
- Budget-constrained decision modeling  
- Marginal value interpretation  
- Strategic recommendation development  

---

These projects demonstrate how optimization techniques support strategic decisions in logistics, retail planning, and sports management under real-world constraints.
