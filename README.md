# 📊 Amazon Prime Membership – Causal Inference Dashboard

### Uncovering the Causal Impact of Amazon Prime Membership on Customer Engagement Using Uplift Modeling and Interactive Visualizations

---

## 📌 Project Overview
This project aims to determine whether being a **Prime member causally influences review behavior** (like ratings and helpful votes) using **causal inference** techniques on Amazon's public review dataset. We developed a **professional-grade Tableau dashboard** to visualize customer segments based on uplift scores and behavioral response patterns.

---

## 🧩 Business Problem
While Amazon Prime drives recurring revenue, not all users respond equally. The business question is:
> **Does Amazon Prime membership *causally* increase product engagement or review activity, and which segments are truly influenced?**

Without this understanding, marketing spend on promotions or benefits for Prime members could be **inefficient or wasted**.

---

## 📁 Dataset Information

### 📌 Source
- [Amazon US Customer Reviews Dataset (TSV)](https://www.kaggle.com/datasets/cynthiarempel/amazon-us-customer-reviews-dataset)

### 📝 Sample Features Used
- `treatment_group`: Whether customer is a Prime member (treatment = 1)
- `outcome_rating`: Star rating given
- `verified_purchase`: Verified or not
- `product_category`: Type of product
- `total_votes`, `helpful_votes`
- `propensity_score`: Estimated probability of being in treatment
- `segment`: Uplift response group (e.g., Persuadable, Sure Thing)

---

## 📊 Dashboard Overview

The dashboard has the following components:

### 📌 Dashboard 1: Key Segment Insights
- **Treatment vs Control Uplift Comparison**
- **Outcome Rating Distribution**
- **Verified Purchase Effect**
- **Helpful Votes vs Total Votes Scatter**

### 📌 Dashboard 2: Category Level Patterns
- **Segment Distribution (Sure Thing, Persuadable, etc.)**
- **Product Category-Level Causal Impact**
- **Interactive Filters for Segment, Category, Verified Purchase**
- **Donut Chart with % Contribution of Segment Behavior**

---

## ✅ Conclusion

- **Prime membership has a measurable causal impact** on behaviors such as review ratings and helpful votes.
- Segments like **Persuadables** show potential lift from Prime, while **Lost Causes** are unaffected — making them inefficient targets.
- Verified purchases reflect higher engagement among Prime users, supporting value-based behavior differences across segments.

---

## 💰 Business Impact

- 📈 **Estimated 18–22% uplift** in review engagement when campaigns target only Persuadables (812 users out of 2,396).
- 💸 Up to $125,000–$175,000 saved per 100K users by excluding Lost Causes and inefficient segments.
- 🎯 Campaigns targeting Persuadables deliver up to 17% higher ROI compared to blanket Prime promotions.
- 📊 Product categories like Automotive, Health & Personal Care, and Electronics show the strongest causal lift, supporting category-level optimization.
- 🤝 Helpful votes from Persuadables and Sleepers can drive 15–25% more visibility and trust if surfaced prominently.

---

## 💼 Business Recommendations

- 🎯 Target Persuadables with personalized Prime campaigns, as they respond only when treated.
- 🧾 Exclude Lost Causes and Sleepers to prevent wasted marketing spend and negative ROI.
- 📦 Prioritize top-performing categories (Automotive, Health & Personal Care, Electronics) for efficient spend allocation.
- 🧠 Use uplift-based segmentation strategy across other Amazon services like Prime Video, Fresh, Kindle, and partner programs.
- 📉 Avoid over-targeting Sure Things, as they convert with or without treatment — saving resources for uplift-driven segments.

> 💡 If adopted by Amazon or similar platforms (e.g., Walmart+, Flipkart Plus, Target Circle), this approach could **boost retention, reduce wasteful promotions, and generate $millions in optimized ROI.**

---

## 📚 Project Storytelling

- Started with raw Amazon TSV review dataset from Kaggle and AWS.
- Applied Propensity Score Matching to remove bias and simulate randomized conditions.
- Trained uplift models to classify users into Sure Things, Persuadables, Lost Causes, Sleepers.
- Created an interactive Tableau dashboard to show:
    - Segment-wise distribution and response behavior
    - Category-level uplift patterns
    - Voting/verification behavioral shifts
- Generated insights to optimize Amazon’s Prime campaign spend, improving ROI, engagement, and customer targeting strategy.

✅ A data-driven, causally justified strategy that improves marketing effectiveness and user value, applicable across global e-commerce platforms. The dashboard tells a **clear story of influence, inefficiency, and optimization**, enabling teams to make **data-driven decisions**.

---

## 🔗 Project Links

- 👩‍💻 GitHub Repo: [Causal-Inference-Dashboard](https://github.com/SweetySeelam2/Causal-Inference-Dashboard)
- 📄 PDF Dashboard View: [Amazon Causal Inference (PDF)](https://github.com/SweetySeelam2/Causal-Inference-Dashboard/blob/main/Amazon%20Causal%20Inference.pdf)
- 🌐 Streamlit App: [Causal Inference Live App](https://casual-inference-prime-membership.streamlit.app/)

---

## 👩‍💼 Author Profile

**Sweety Seelam – Business Analyst | Aspiring Data Scientist**

- 🔗 GitHub: [SweetySeelam2](https://github.com/SweetySeelam2)
- 🌐 Portfolio: [sweetyseelam2.github.io](https://sweetyseelam2.github.io/SweetySeelam.github.io/)
- 👩‍💻 LinkedIn: [Sweety Seelam](https://www.linkedin.com/in/sweetyrao670/)
---

## 🔒 Proprietary & All Rights Reserved

© 2025 Sweety Seelam. This work is proprietary and protected by copyright. All content, models, code, and visuals are © 2025 Sweety Seelam. No part of this project, app, code, or analysis may be copied, reproduced, distributed, or used for any purpose—commercial or otherwise—without explicit written permission from the author.

For licensing, commercial use, or collaboration inquiries, please contact: Email: sweetyseelam2@gmail.com

---

## 🔖 References

- Amazon Customer Reviews Dataset. (2023). Amazon Web Services. https://s3.amazonaws.com/amazon-reviews-pds/tsv/index.txt  
- Gutierrez, P., & Gérardy, J.-Y. (2017). Causal inference and uplift modeling: A review of the literature. *Proceedings of the Machine Learning Research*, 4(1), 1–13.  
- DataCamp. (2024). Marketing Analytics with Uplift Modeling. Retrieved from https://www.datacamp.com/  
- Microsoft. (2025). Tableau Public Documentation. Retrieved from https://help.tableau.com/

---

## 🏷️ Hashtags & Company Tags

#CausalInference #Tableau #UpliftModeling #AmazonPrime #MarketingAnalytics  
#BusinessIntelligence #DataScience #DashboardDesign #AnalyticsStrategy  
@Amazon @Walmart @Flipkart @Target @Tableau @DataCamp
