#  SQL Case Study – Business Insights

##  Problem Statement

The business aimed to analyze customer behavior, revenue trends, and retention performance using raw transactional data.

---

##  Objectives

* Identify top revenue-generating customers
* Track monthly revenue trends and growth
* Analyze customer retention and repeat behavior
* Understand funnel conversion performance

---

##  Tools Used

* SQL (MySQL / SQLite)
* DB Browser / SQL Editor

---

##  Key Analysis

###  Top Customers by Revenue

Output: ![Top Customers](images/sql1.png)
Insight: A small group of customers contributes a significant portion of total revenue, highlighting the importance of focusing on high-value users.

---

###  Conversion Metrics

Output: ![Conversion Metrics](images/sql2.png)
Insight: The overall conversion rate (~40%) is relatively low, indicating inefficiencies in converting users into paying customers.

---

###  Funnel Analysis

Output: ![Funnel Analysis](images/sql3.png)
Insight: A major drop-off is observed between signup and purchase stages, suggesting friction in the conversion journey.

---

###  Time Series Analysis (Revenue Trends)

Output: ![Revenue Trends](images/sql4.png)
Insight: Revenue shows fluctuations with a decline in recent months, indicating possible demand issues or ineffective campaigns.

---

###  Monthly Growth Rate

Output: ![Growth Rate](images/sql5.png)
Insight: Negative growth in later months reflects a declining business performance trend.

---

###  Repeat Purchase Rate

Output: ![Repeat Rate](images/sql6.png)
Insight: A low repeat purchase rate (~40%) suggests weak customer retention.

---

###  Cohort Analysis

Output: ![Cohort Analysis](images/sql7.png)
Insight: Most customers drop off after the first month, indicating onboarding and engagement issues.

---

###  RFM Segmentation

Output: ![RFM Segmentation](images/sql8.png)
Insight: Revenue is driven by a small group of high-value customers, while a large segment is at risk of churn.

---

##  Key Insights

* Revenue is concentrated among a few customers
* Significant drop in the conversion funnel
* Declining revenue growth trend
* Low repeat purchase rate
* Weak customer retention

---

##  Business Recommendations

* Focus on high-value customers through loyalty programs
* Improve checkout and purchase experience
* Launch retention and re-engagement campaigns
* Optimize marketing strategies during low-performing periods
* Target at-risk customers with personalized offers

---

##  SQL Queries


│── queries.sql


---

##  Conclusion

This project demonstrates end-to-end SQL analysis, covering customer behavior, conversion funnel, revenue trends, and retention strategies to support data-driven business decisions.
