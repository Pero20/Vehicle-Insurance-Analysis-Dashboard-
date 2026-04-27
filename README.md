# Vehicle-Insurance-Analysis-Dashboard-
This dashboard helps identify high-risk customers, understand claim behavior across segments, and highlight profitable low-risk groups, enabling insurers to optimize pricing strategies, reduce risk exposure, and improve overall business performance.
🔹 Dataset
📌 Source of Data
https://docs.google.com/spreadsheets/d/1IiaOffH0rZPapfLhuUXqoTBS6s8FaLF4/edit?usp=drivesdk&ouid=107737330306325874232&rtpof=true&sd=true
📌 1. Business Context
Insurance companies operate on a simple principle:
Price risk accurately while maximizing customer value.
However, this becomes difficult when:
Customer risk profiles are unclear
Claim behavior isn’t well understood
Pricing strategies are not data-driven
This project was developed to analyze risk distribution, claim frequency, and income patterns in order to improve underwriting decisions and revenue optimization.
🎯 2. Problem Statement
The business lacked:
Clear segmentation of high-risk vs low-risk customers
Visibility into how income and demographics affect claims
A structured way to identify profitable vs risky customers
A centralized dashboard for decision-making
👉 Result: Inefficient pricing, increased claim costs, and missed revenue opportunities.
📊 3. Analytical Approach
Step 1: Data Preparation
Cleaned and transformed raw insurance data using Power Query
Standardized:
Age categories
Income levels
Risk classifications
Step 2: Data Modeling
Built relationships between:
Customers
Claims
Income segments
Created calculated columns for:
Risk Level
Age Category
Step 3: KPI Development (DAX)
Key metrics created:
Total Customers
Average Claim Frequency
High-Risk Customer %
Average Income
Step 4: Visualization Strategy
Designed dashboard with decision-first layout:
Left panel → KPIs (executive summary)
Center → Claim behavior (age, income)
Right → Risk distribution
Bottom → Behavioral insights (car attributes)
📈 4. Key Findings
1. Risk vs Revenue Imbalance
Low-risk customers contribute ~88% of total income
High-risk customers are fewer but financially dangerous
👉 Insight: Revenue is heavily dependent on safe customers
2. Claim Behavior by Demographics
Adults & Elderly = highest claim frequency (~37% each)
Younger customers contribute less to claims
👉 Insight: Risk increases with age-related factors
3. Income vs Claim Relationship
Medium-income customers show higher claim activity
Low-income customers have minimal claims
👉 Insight: Risk is not linear with income
4. Customer Distribution
Majority of customers = Low Risk
Small % of High Risk drives disproportionate exposure
👉 Insight: Classic insurance risk concentration
5. Behavioral Signals (Car Attributes)
Certain car colors show higher claim frequency
👉 Insight: Potential proxy for behavioral or demographic clustering
🚨 5. Business Impact
If implemented, this dashboard enables:
Better Pricing Models
→ Adjust premiums based on risk segments
Loss Reduction
→ Identify and manage high-risk customers early
Customer Retention
→ Focus on profitable low-risk customers
Strategic Decision-Making
→ Replace guesswork with real-time insights
🚀 6. Recommendations
🎯 1. Risk-Based Pricing
Increase premiums for high-risk customers
Offer incentives for low-risk behavior
🤝 2. Customer Segmentation Strategy
Tier customers into:
High Value (Low Risk + High Income)
Monitor (Medium Risk)
Control (High Risk)
📉 3. Claims Reduction Strategy
Introduce safe-driving rewards
Monitor high-claim segments (Adults/Elderly)
💰 4. Revenue Optimization
Upsell premium packages to low-risk customers
Cross-sell insurance add-ons
