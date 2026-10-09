# YuvaIntern – Logistics Data Analyst Internship

A portfolio of logistics data analysis projects completed during my internship at YuvaIntern, using Python, data analysis, data visualization, and machine learning to derive actionable business insights.

## 📌 About the Project

This repository documents my weekly assignments focused on understanding logistics operations, analyzing delivery performance, preparing datasets, and applying predictive modeling techniques to support data-driven decision-making.

## 📂 Weekly Assignments

| Week | Project | Key Activities |
|---|---|---|
| Week 1 | Logistics Data Analysis | Exploratory data analysis and logistics performance insights |
| Week 2 | Data Preprocessing | Data cleaning, handling missing values, and feature preparation |
| Week 3 | Advanced Data Analysis | Delivery performance analysis, order trends, and visualizations |
| Week 4 | Predictive Modeling & Optimization | Delivery-time prediction, model comparison, feature importance, and high-risk order identification |

## 🛠️ Technologies Used

- **Programming:** Python
- **Data Analysis:** Pandas, NumPy
- **Visualization:** Matplotlib, Seaborn
- **Machine Learning:** Scikit-learn
- **Environment:** Google Colab, Jupyter Notebook
- **Version Control:** Git and GitHub

## 🤖 Week 4: Predictive Modeling

The Week 4 project uses the Olist e-commerce dataset to predict delivery time in days.

### Models Evaluated
- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor

### Model Performance

| Model | MAE (Days) | RMSE (Days) | R² Score |
|---|---:|---:|---:|
| Linear Regression | 6.27 | 9.80 | 0.041 |
| Decision Tree | 5.48 | 9.30 | 0.136 |
| Random Forest | 5.39 | 8.99 | 0.193 |

Random Forest achieved the best results among the three evaluated models.

### Key Findings
- Total freight was the most influential feature in the Random Forest model.
- Total price was the second most influential feature.
- The example order received a predicted delivery time of **9.92 days**.
- The high-risk screening rule flagged **1,466 test orders (7.60%)** with predicted delivery times exceeding 20 days.

### Optimization Recommendations
- Identify potentially delayed orders before delivery.
- Improve freight and carrier allocation decisions.
- Use predicted delivery times to support delivery planning.
- Incorporate location, distance, and carrier-performance data to improve future model accuracy.

## 🎯 Skills Demonstrated

- Exploratory Data Analysis (EDA)
- Data Cleaning and Preprocessing
- Feature Engineering
- Data Visualization
- Regression Modeling
- Model Evaluation using MAE, RMSE, and R²
- Feature Importance Analysis
- Logistics Performance Optimization
- GitHub Project Documentation

## 📁 Repository Structure

```text
YuvaIntern-Logistics-Data-Analyst/
├── Week-1/
├── Week-2/
├── Week-3/
├── Week-4/
└── README.md
```

Each weekly folder contains the corresponding assignment files and analysis deliverables.

## 👩‍💻 Author

**Srushti Titarmare**

B.Tech – Data Science

GitHub: [@Srushti070](https://github.com/Srushti070)

---

*This repository represents my practical learning and project work in logistics analytics, Python, and machine learning.*
