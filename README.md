# Data-analytics-using-Gen-AI

## 📌 Project Overview
This project focuses on **predicting loan delinquency risk** for customers of Geldium’s Collections team using financial and behavioral data. The goal is to improve repayment efficiency, reduce missed payments, and enable proactive support through **AI-driven insights**.

## 🗂️ Project Files
- **Dataset**: `Delinquency_prediction_dataset.xlsx` – Customer-level financial and repayment data.  
- **EDA Report**: `EDA_SummaryReport_Template_komal.docx` – Exploratory analysis, missing data handling, and key insights.  
- **Model Plan**: `Task 2_ModelPlan_Template_komal.docx` – Model pipeline (Logistic Regression), metrics, and justification.  
- **Business Report**: `Updated_Business_Summary_Report_Template_komal3.docx` – Predictive insights, actionable recommendations, and ethical AI considerations.  
- **Presentation**: `Presentation_Template_komal4.pptx` – Final slide deck explaining system design, agentic AI role, and expected business impact.  

## 📊 Dataset Description
**Key findings from EDA**:
- High credit utilization increases likelihood of missed payments.  
- Low credit scores strongly correlate with delinquency.  
- Lower income + higher debt-to-income ratio signals higher risk.  
- Missing values were treated with mean/median imputation. :contentReference[oaicite:4]{index=4}
  
## 🤖 Model Approach
We used a **Logistic Regression** model because:  
- ✅ High interpretability (important for financial domain)  
- ✅ Easy to deploy, efficient in low-compute environments  
- ✅ Accepted by regulators due to transparency  

**Evaluation Metrics**: Accuracy, Precision, Recall, F1 Score, AUC-ROC
- AUC > 0.80 achieved → strong separation between delinquent vs non-delinquent customers.  

## 🛠️ Tools & Technologies
- **Python** (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)  
- **Excel** (Initial data review)  
- **PowerPoint** (Business presentation)  
- **MS Word** (Reports)  
- **AI/GenAI** (assisted in EDA summary and anomaly detection)  

## 📌 Business Recommendations
Based on model insights:
- Customers with **credit utilization >75%** and **≥1 missed payment** are high risk.  
- Launch **Pre-Delinquency Outreach Program** → reminders, counseling, and flexible payment plans.  
- Monitor fairness via subgroup audits (income levels, age groups, employment status).  

## 📈 Expected Business Impact
- 🔻 15–20% reduction in delinquency rates among high-risk customers  
- 💰 Cost savings in collections and recovery efforts  
- ✅ Enhanced customer trust and brand reputation  
