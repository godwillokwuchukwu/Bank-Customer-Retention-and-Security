# Enhancing Bank Customer Retention and Security

I analyzed over 1 million real-world banking transactions to address two of the most critical challenges in financial services: **fraud risk** and **customer churn**. Using Python-based analytics and machine learning, I developed models that detect anomalous transactions, predict customer churn, and segment customers for targeted retention strategies.

Beyond technical execution, this project demonstrates my ability to translate complex data into **actionable business insights** for executives, investors, and operational leaders—supporting improved security, revenue retention, and long-term growth.

---

### Project Objectives

The analysis was structured around three core objectives:

1. **Fraud Detection**
   Identify suspicious transactions and behavioral anomalies to strengthen financial security and reduce losses.

2. **Customer Churn Prediction**
   Forecast churn risk, quantify churn rates, and identify behavioral drivers impacting customer retention.

3. **Customer Segmentation (RFM Analysis)**
   Segment customers using Recency, Frequency, and Monetary metrics to enable personalized engagement and maximize customer lifetime value (CLV).

The dataset comprised **1,048,567 transactions from 839,081 customers**, spanning **August–October 2016**, offering a realistic snapshot of banking behavior at scale.

---

### Data Preparation and Feature Engineering

A robust preprocessing pipeline was established to ensure analytical accuracy and model reliability.

**Key Steps Included:**

* Parsing and standardizing date fields to calculate customer age and transaction recency.
* Handling missing values in critical customer attributes to prevent biased modeling.
* Engineering behavioral features such as transaction hour, balance changes, high-value transaction flags, and encoded demographic variables.

This phase significantly improved data quality and enabled more accurate fraud and churn modeling, reinforcing the principle that high-quality insights begin with well-prepared data.

---

### Customer Behavior Aggregation (RFM Framework)

Transactions were aggregated at the customer level to construct an RFM-style behavioral dataset, including:

* **Recency:** Days since last transaction
* **Frequency:** Transaction count
* **Monetary:** Total, average, and variability of spend
* **Additional Metrics:** Average balance, age, transaction timing, and geographic diversity

This transformation converted raw transaction logs into customer-centric intelligence, forming the foundation for both churn prediction and segmentation strategies.

---

### Fraud Detection Analysis

An **Isolation Forest** model was applied to detect anomalous transactions in a high-dimensional feature space.

**Results:**

* Identified approximately **1% of transactions** as suspicious, consistent with industry benchmarks.
* Key fraud indicators included unusually high transaction amounts, abnormal transaction times, and post-transaction balance irregularities.

**Business Impact:**
Early detection of anomalous behavior enables proactive fraud mitigation, reduces financial losses, and strengthens customer trust, critical factors for operational resilience and investor confidence.

---

### Customer Churn Prediction

Churn was modeled using an **XGBoost classifier**, with churn defined by prolonged inactivity.

**Model Performance:**

* Achieved near-perfect predictive accuracy and ROC-AUC, indicating strong behavioral signals.
* **Recency** emerged as the most influential predictor, followed by transaction frequency and spending variability.

**Business Insight:**
Customers with declining engagement and erratic transaction patterns are significantly more likely to churn. Targeted interventions for these segments can materially improve retention and revenue stability.

---

### Customer Segmentation (RFM Clustering)

Using K-Means clustering, customers were grouped into four strategic segments:

* **Champions (8%)** – High value, highly engaged
* **Loyal Customers (43%)** – Stable and consistent
* **At-Risk Customers (24%)** – Declining engagement
* **Hibernating Customers (25%)** – Dormant accounts

This segmentation supports precision marketing, loyalty programs, and proactive retention initiatives.

---

### Strategic Insights for Stakeholders

* **Executives & Investors:**
  While fraud levels are currently manageable, high churn represents a major revenue leakage. Retention-focused analytics present a significant upside opportunity.

* **Operations & HR Leaders:**
  Demographic and behavioral patterns reveal where customer experience and engagement strategies should be reinforced.

* **Investment Perspective:**
  Institutions that effectively deploy predictive analytics for fraud prevention and retention can achieve higher CLV, improved margins, and scalable growth.

---

### Recommendations and Growth Roadmap

**Short-Term (2–5 Years):**

* Deploy real-time fraud monitoring systems.
* Launch data-driven re-engagement campaigns for at-risk customers.
* Strengthen loyalty programs for high-value segments.

**Long-Term (5–10 Years):**

* Automate retention strategies using churn probability scores.
* Expand product offerings informed by behavioral and demographic insights.
* Institutionalize a data-driven decision culture across the organization.

---

### Conclusion

This project demonstrates how advanced analytics can transform banking operations from reactive to predictive. By integrating fraud detection, churn prediction, and customer segmentation, financial institutions can protect assets, retain customers, and drive sustainable growth.

I welcome conversations on how these skills and insights can deliver value within your organization.

---

**Skills Demonstrated:**
Python (Pandas, Scikit-learn, XGBoost), Data Preprocessing, Machine Learning, Feature Engineering, Customer Analytics, Business Storytelling, Data Visualization

*Attachments: Churn feature importance visualization and project notebook*
