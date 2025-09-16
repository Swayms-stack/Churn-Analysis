# 🐾 Customer Churn Analysis – Data-Driven Retention Strategies

Customer churn is one of the biggest threats to subscription businesses—losing existing customers is often far more costly than acquiring new ones. 
This project applies predictive analytics and machine learning to a dataset of subscription records to identify why customers leave and how to intervene effectively. 
The results are not just technical scores—they translate directly into business actions. 
These insights provide a data-driven foundation for decision-making that balances operational efficiency with customer satisfaction.

## 📖 Table of Contents
- [Overview](#overview)
- [Key Findings](#key-findings)
- [Technologies](#technologies)
- [Visualizations](#visualizations)
- [Authors](#authors)
- [License](#license)

---

## 📌 Overview

This project addresses a critical challenge for subscription-based businesses: **customer churn**. Leveraging a dataset of 20,000 customer records across 29 demographic, behavioural, and transactional variables, we applied advanced analytics and machine learning to predict churn and reveal the drivers behind customer retention.

Through **data exploration, feature engineering, and rigorous model evaluation**, we compared multiple algorithms—Logistic Regression, Random Forest, XGBoost, and LightGBM—selecting **LightGBM** as the top performer with an **87.4% accuracy** and **0.88 AUC-ROC**. Key churn indicators included transaction frequency, subscription tier, customer tenure, and payment issues.

Most importantly, the analysis transforms technical findings into **actionable retention strategies** - personalized subscription upgrades, targeted engagement campaigns, loyalty programs, and automated alerts for high-risk customers. By applying these strategies, businesses can **reduce churn, protect recurring revenue streams, and increase customer lifetime value**, driving long-term profitability and growth.

---

## 🔎 Key Findings
- **Middle-aged customers (29–51)** showed the highest churn risk.  
- **Longer transaction gaps** strongly increased churn likelihood.  
- **Lower-tier subscription plans** had significantly higher churn rates.  
- **Loyalty status and transaction frequency** reduced churn risk.  
- **LightGBM** outperformed other models (Accuracy: **87.4%**, AUC-ROC: **0.88**).

---

## 🛠 Technologies
- **Languages/Tools**: R, Quarto (`.qmd`)
- **ML Models**: Logistic Regression, Random Forest, XGBoost, LightGBM  
- **Visualization**: Matplotlib, Seaborn  
- **Documentation**: Markdown, Quarto

---
