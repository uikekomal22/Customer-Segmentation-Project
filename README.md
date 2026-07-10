## Project 2: Customer Segmentation for Targeted Marketing

* **Objective:** Group a consumer base of 200 profiles using unsupervised machine learning to isolate distinct purchasing personas based on demographic metrics and spending behaviors.
* **Tools Used:** Python (Jupyter Notebook via Anaconda Navigator), 
.
* **Methodology:** Implemented data exploration, feature normalization, and **K-Means Clustering** to separate accounts mathematically without human bias, followed by a custom ETL pipeline in Power Query.
* **Key Outcome:** Extracted 5 distinct customer groups and deployed an executive **Customer Segmentation Dashboard** displaying key metric volumes, distribution maps, and structural commercial recommendations.

---

### Project Architecture & Implementation Pipeline

#### 1. Python Algorithmic Core
* Used `pandas` and `scikit-learn` to process raw customer profiles containing `Annual Income (INR)` and `Spending Score (1-100)`.
* Executed feature standardization and tuned the **K-Means Clustering** engine to assign mathematically verified segment labels (`Cluster_ID`) to each customer record based on spatial density.

#### 2. Power BI Executive Visual Layer
* Built an analytical dashboard tracking key high-level indicators including **Total Customers (200)**, **Average Income (60.56K INR)**, and structured performance tables.
* Deployed interactive elements to analyze customer positions across three primary analytical views:
  * **Customer Distribution Donut Chart:** Visually separates market volume share across the 5 discovered segments.
  * **Income vs. Spending Behavior Plot:** Charts the distribution of average spending indexes across calculated annual earning thresholds.
  * **Segment Performance Granular Table:** Shows a clean view linking individual `Customer IDs` directly to their respective spending characteristics.

---

### Discovered Customer Segments & Volume Analytics

Based on the dashboard analysis, the 200 customers are distributed across 5 distinct strategic archetypes:

| Customer Segment | Volume Count | Market Share (%) | Data Profile Characteristics | Targeted Marketing Strategy |
| :--- | :--- | :--- | :--- | :--- |
| **Middle Income Customers**| 72 | 36% | Moderate income, mid-tier spending profile. | **Growth Opportunities:** Target with loyalty upgrades and cross-selling. |
| **Regular Customers** | 64 | 32% | Standard baseline income and spending metrics. | **Baseline Retention:** Use seasonal campaigns to keep purchasing steady. |
| **Budget Customers** | 42 | 21% | Low annual income with restricted spending habits. | **Engagement Campaigns:** Focus on value offerings and active discounts. |
| **High Value Customers** | 16 | 8% | Higher income brackets with solid spending scores. | **VIP Perks:** Offer early product releases and dedicated perks. |
| **Premium Customers** | 6 | 3% | Top-tier earnings paired with maximum spending scores. | **Exclusivity:** Direct high-end marketing and personal luxury offers. |

---

### Core Business Insights Implemented
* **Premium Asset Identification:** High-income and high-spending customers represent the company's highest-value segment. They require premium rewards to ensure long-term customer lifetime value (CLV).
* **Untapped Growth Opportunities:** Customers with high annual income but moderate spending behaviors are primary targets for proactive cross-selling.
* **Churn Mitigation:** Low-spending clusters (such as Budget Customers) are flagged to receive active engagement campaigns and personalized marketing tracks to improve overall retention metrics.
