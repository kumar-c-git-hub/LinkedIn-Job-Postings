# 💼 LinkedIn Job Postings Analytics 

🚀 **Project Overview**  
This project analyzes over 10,000 LinkedIn job postings across the United States (2023–2024) to uncover recruitment trends, salary patterns, remote work demand, and factors influencing candidate applications. The analysis integrates job postings, company data, and benefits data to provide a complete view of hiring performance and job market behavior.  
This project simulates real-world HR analytics scenarios, helping organizations make data-driven hiring decisions and optimize recruitment strategies.

---

## 🎯 Objectives
- Analyze salary trends across job domains, experience levels, and locations  
- Measure job posting effectiveness using views, applications, and sponsored status  
- Identify high-demand remote roles and hybrid work trends  
- Evaluate recruitment efficiency using apply-to-view ratios  
- Understand how company size, industry, and benefits impact applications  
- Identify geographic hiring hotspots across US states and cities  
These objectives align with real business challenges faced by HR teams and talent acquisition departments in competitive job markets.

---

## 🛠️ Tools & Technologies
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Plotly  
- Google Colab  
These tools were used for end-to-end data analysis, from preprocessing to advanced visualization and insight generation.

---

## 📂 Dataset
- **Source:** Data.world (LinkedIn Job Postings RDB Dataset)  
- **Records:** 10,000+ job postings  
- **Time Period:** 2023–2024  
- **Structure:** 3 relational datasets  

### Dataset Tables
- **Posting:** Job details (title, salary, views, applies, remote, etc.)  
- **Company:** Industry, employees, location  
- **Benefits:** Medical and additional benefits  

The relational structure of the dataset enables deeper analysis by combining job-level, company-level, and benefits-level information.

---

## ⚙️ Project Workflow

### 1. Data Loading
- Imported multi-sheet Excel dataset using Pandas  
- Extracted and structured posting, company, and benefits tables  
This step ensured proper separation of relational data for efficient preprocessing and analysis.

### 2. Data Cleaning
- Handled missing values using hierarchical imputation  
- Removed duplicates and standardized formats  
- Cleaned categorical variables and text fields  
Data cleaning improved data quality and ensured reliable analysis by maintaining logical consistency across datasets.

### 3. Feature Engineering
Created new analytical features:
- **Apply Rate = Applies / Views**  
- **Competition Level = Views – Applies**  
- **High Demand Flag** (above median applications)  
- **Compensation per View**  
- **Remote Advantage**  
These engineered features provided deeper insights into recruitment performance and candidate behavior.

### 4. Data Integration
- Merged all datasets into a single dataset: `linkedin_jobs`  
This unified dataset allowed comprehensive analysis across multiple dimensions such as salary, company, and benefits.

### 5. Exploratory Data Analysis (EDA)
- Performed univariate, bivariate, and multivariate analysis  
- Used statistical measures: mean, median, variance, skewness  
- Built visualizations: histograms, box plots, scatter plots, heatmaps  
EDA helped identify patterns, relationships, and anomalies within the dataset to support data-driven conclusions.

---

## 📊 Key Analysis Areas

### 📌 Recruitment Effectiveness
- Strong positive relationship between **views and applications**  
- Many postings have low conversion rates (views ≠ applications)  
This highlights the importance of improving job quality and engagement, not just visibility.

### 💰 Compensation Insights
- Salaries vary significantly across job domains and industries  
- High-paying roles concentrated in specialized fields  
This helps organizations benchmark competitive salaries and job seekers identify lucrative domains.

### 🌍 Remote Work Trends
- Remote jobs attract more applications  
- Remote work is a strong recruitment advantage  
The findings reflect the growing preference for flexible work arrangements in the modern workforce.

### 🏢 Company & Industry Impact
- Larger companies tend to attract more applicants  
- Certain industries consistently receive higher applications  
Company reputation and industry demand play a key role in influencing candidate decisions.

### 🎁 Benefits Influence
- Jobs offering medical benefits receive significantly more applications  
This shows that total compensation (salary + benefits) strongly impacts job attractiveness.

### 📍 Geographic Insights
- Hiring is concentrated in specific states and cities  
- Regional hotspots indicate strong job market demand  
Geographic analysis helps companies focus recruitment efforts in high-demand areas.

---

## 📈 Key Insights
- Higher visibility increases applications  
- Recruitment conversion rates are generally low  
- Remote roles significantly boost candidate interest  
- Benefits improve job attractiveness  
- Salary alone does not guarantee higher applications  
- Hiring demand is geographically concentrated  
These insights provide actionable recommendations for optimizing recruitment strategies.

---

## 💡 Conclusion
This project demonstrates how data analytics can improve recruitment strategy by identifying key drivers of job posting success. Organizations can optimize hiring by focusing on visibility, remote flexibility, benefits, and strategic locations.  
It also highlights the importance of combining multiple data sources to gain a holistic understanding of workforce trends.

---

## 📌 Future Improvements
- Build machine learning models to predict job applications  
- Perform NLP analysis on job descriptions  
- Create interactive dashboards (Power BI / Streamlit)  
- Extend dataset with more recent data  
These enhancements can transform the project into a predictive and real-time analytics solution.

---

## 🔗 Project Link
👉 https://colab.research.google.com/drive/1m8g5XTALT5PeIsVak8H3mFhO1t_1ybMw

---

## 🙌 Acknowledgment
This project was developed as part of my data analytics learning journey to strengthen practical skills in Python and real-world HR analytics.  
It reflects hands-on experience in solving business problems using data-driven approaches.

---

## 📬 Contact
**KUMAR C – Data Analyst**  
💼 LinkedIn: kumar C  
📧 Email: kumarak04122021@gmail.com  

---

## 📚 Tags
`#Python` `#DataAnalytics` `#HRAnalytics` `#RecruitmentAnalytics` `#EDA` `#DataVisualization` `#LinkedInData` `#MachineLearningReady`
