# 📊 HR Analytics: Predicting Employee Turnover

An end-to-end project to understand and predict employee turnover using data analysis, SQL, visualizations, machine learning, and deployment of a predictive model.

---

## 📑 Table of Contents

- [📌 Project Summary](#project-summary)
- [🎯 Part 1: Targeted Insights](#part-1-targeted-insights)
- [📈 Part 2: Visualizations (Tableau)](#part-2-visualizations-tableau)
- [🔍 Part 3: Perform EDA](#part-3-perform-eda)
- [🤖 Part 4: Perform Machine Learning](#part-4-perform-machine-learning)
- [🚀 Part 5: Deploy the Model](#part-5-deploy-the-model)
- [📝 Application and Recommendations](#application-and-recommendations)
- [⚠️ Assumptions Taken if Any](#assumptions-taken-if-any)

---

## 📌 Project Summary

**Project Statement**:  
Portobello Tech is an app innovator aiming to predict employee turnover. The company evaluates employees based on factors like:

- Number of projects
- Average monthly working hours
- Time spent in the company
- Promotions in the last 5 years
- Salary level
- Job satisfaction and evaluation scores

As a **Data Analyst in the HR Department**, my role is to:

- Extract insights for relevant departments (finance/marketing)
- Explore employee turnover trends
- Build a predictive model
- Deploy an interactive app to predict attrition

---

## 🎯 Part 1: Targeted Insights

Using **SQL**, I extracted targeted insights for:

- 📦 MacBook sales patterns  
- 💰 Refund rates  
- 📣 Top-performing marketing channels

These insights helped the finance and marketing teams focus on what drives ROI and satisfaction.

---

## 📈 Part 2: Visualizations (Tableau)

Interactive dashboard highlights turnover across departments, genders, age groups, and educational backgrounds.

📊 **Key Metrics Displayed**:
- Total employee count
- Turnover count and rate
- Department-wise and education-wise segmentation

📌 **Key Findings**:
- Total Employees: 14,999  
- Average Age: 42 years  
- Overall Turnover Rate: **24%**  
- Majority in the **30–40** age group  
- Sales department has the **highest turnover**  
- **Graduates** have higher turnover; **PhD holders** have the lowest

> 🔗 [**View Interactive Dashboard**](#) *(replace with actual Tableau Public or GitHub Pages link)*

![Dashboard Preview](https://via.placeholder.com/800x400.png?text=Dashboard+Image)

---

## 🔍 Part 3: Perform EDA

Using Python (Pandas, Matplotlib, Seaborn):

- Explored turnover based on satisfaction, evaluation, salary category, working hours, etc.
- Discovered patterns related to burnout and lack of promotions
- Identified correlations between variables and turnover behavior

---

## 🤖 Part 4: Perform Machine Learning

### Goals:
- Cluster employees who left using **satisfaction** and **evaluation**
- Identify **important features** causing turnover
- Build a predictive model to classify if an employee will **stay** or **leave**

📌 Techniques Used:
- K-Means Clustering  
- Feature Importance via Random Forest  
- Classification using Logistic Regression, Decision Tree, and Random Forest  

---

## 🚀 Part 5: Deploy the Model

Built a **Streamlit Web App** that:

- Accepts input for satisfaction, evaluation, salary level, etc.
- Predicts whether an employee will stay or leave
- Offers immediate insights for HR decision-making

🔗 [**Launch App Here**](#) *(replace with actual Streamlit link)*

![App Screenshot](https://via.placeholder.com/800x400.png?text=App+UI+Preview)

🎬 [Watch Demo Video](#) *(replace with YouTube or local video link)*

---

## 📝 Application and Recommendations

- Improve retention by focusing on early-stage employee engagement
- Tailor retention strategies to departments like Sales and younger age groups
- Review workloads and project counts to avoid burnout
- Use this tool in HR screening and post-evaluation workflows

---

## ⚠️ Assumptions Taken if Any

- Data is anonymized and representative of all departments
- Education background is self-reported and assumed accurate
- Employee satisfaction scores are based on internal survey methodology

---

## 📁 Project Files

- [📄 Report PDF](./HR_Analytics_Report.pdf)
- [📊 Dataset CSV](./employee_data.csv)
- [🧠 Trained Model](./models/turnover_model.pkl)
- [🖥️ Streamlit App Code](./app/streamlit_app.py)

---

## 📜 License

This project is licensed under the MIT License. See [LICENSE](./LICENSE) for more details.
