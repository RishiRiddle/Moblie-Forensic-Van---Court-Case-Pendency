# Moblie-Forensic-Van---Court-Case-Pendency
# 🚓 Mobile Forensic Van Analytics

### 🔍 Problem Statement
Court case pendency is increasing significantly in Uttar Pradesh, India. 
One major reason identified is the **delay or non-submission of forensic reports** by labs, or associated departments. 
This impacts timely investigation, judicial proceedings, and public trust in the system.

### 🎯 Goal
To **analyze the root causes** of delayed or missing forensic report submissions, 
build a **predictive analytics solution**, and 
provide **actionable insights** to help decision-makers 
to improve forensic workflow efficiency and reduce case pendency.

---

| Category | Tools |
|---------|-------|
| 🔢 Data Science | Python, Pandas, Scikit-learn, XGBoost, SHAP |
| 📊 BI & EDA | Power BI (DAX), Seaborn, Matplotlib |
| 🧱 ETL & Data Wrangling | Alteryx, SQL, Google Colab |
| ☁️ Cloud & Storage | AWS S3, AWS EC2 |
| 🐳 Containers | Docker, Kubernetes |
| 🧠 Model Deployment | Streamlit, Flask (optional) |
| 📦 Model Tracking | MLflow |
| 💾 Data Warehouse | Snowflake |
| 🔐 Version Control | Git, GitHub |

---

## 📊 Data Sources

- Police Case & FIR logs
- Forensic Lab Submission Records
- Mobile Forensic Van Attendance Logs
- Court Case Status Data
- Administrative Metadata (officer, region, case type)

---

## 📈 Key Deliverables

- 📋 **Exploratory Data Analysis**: Identify trends, bottlenecks, and common delay points
- 🔍 **Feature Engineering**: Build delay-related features (e.g., district, lab, van usage, evidence type)
- 🤖 **Predictive Model**: Forecast likelihood of report delay using classification models
- 📊 **Power BI Dashboard**: Visual analytics for leadership to monitor KPIs and take corrective actions
- 📌 **Recommendations**: Actionable suggestions to improve coordination, efficiency, and resource allocation

---

## 🚀 Deployment Plan

- 📍 **Streamlit App**: For demo of model predictions and insights
- 📍 **Docker Container**: To package the ML model and app for deployment
- 📍 **Kubernetes**: For scalable container orchestration
- 📍 **AWS EC2**: To host the deployed solution
- 📍 **Power BI Dashboard**: For interactive analysis accessible to forensic and government officers
- 📍 **GitHub Repository**: For complete codebase, documentation, and version tracking

---

## 👥 Target Audience / Stakeholders

- **Forensic Department, Govt. of Uttar Pradesh**
- **Judiciary and Administrative Departments**
- **Police & Crime Scene Investigation Units**
- **Policy Makers & Law Enforcement Agencies**

---

## 🔁 Project Workflow

### ✅ Step-by-Step (Text-Based)

1. **Define Problem Statement** – Understand the scope of report delays and case pendency  
2. **Identify & Collect Data** – From forensic labs, police records, mobile van logs  
3. **ETL Pipeline Setup** – Use Python/Alteryx to clean, transform, and load data  
4. **Exploratory Data Analysis (EDA)** – Analyze patterns, bottlenecks, time gaps  
5. **Feature Engineering** – Create predictive features (e.g., van usage, report delay, region type)  
6. **Model Training** – Use classification models (Random Forest, XGBoost)  
7. **Model Evaluation** – Use metrics like AUC, Recall, F1-Score; visualize with SHAP  
8. **Dashboard Development** – Use Power BI to display KPIs and insights  
9. **Containerization** – Package the app using Docker; orchestrate with Kubernetes  
10. **Deployment** – Launch the model & dashboard via Streamlit on AWS  
11. **Stakeholder Delivery** – Share dashboards and insights with forensic and legal departments

---

### 🖼️ Visual Workflow Diagram

![Workflow](docs/workflow.png)

> *(Place your workflow image in a folder called `/docs/` and name it `workflow.png` to make this display properly)*

---

## 📁 Project Structure
