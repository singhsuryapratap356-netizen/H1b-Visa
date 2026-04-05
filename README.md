# 📊 H-1B Visa Data Analysis Dashboard  
### *(SQL + Python + Power BI Project)*

---

## 📌 Project Overview  
This project is an **end-to-end data analytics solution** that analyzes H-1B visa applications using **SQL, Python, and Power BI**.  

The objective is to transform raw visa data into actionable insights related to:
- Application trends  
- Approval and denial rates  
- Job demand  
- Salary distribution  
- Employer and location analysis  

The final output is an **interactive dashboard** that helps understand key factors influencing H-1B visa outcomes.

---

## 🎯 Objectives  
- Analyze total applications, approvals, and denials  
- Identify top job roles in demand  
- Understand wage distribution across job categories  
- Explore geographic trends (state & city level)  
- Identify top companies sponsoring H-1B visas  

---

## 🔄 Project Workflow  

### 1️⃣ Data Collection  
- Dataset sourced from H-1B visa disclosure data (multiple quarters)

### 2️⃣ Data Storage (SQL)  
- Created database and tables using MySQL  
- Imported large CSV datasets  

📄 SQL Script: H1B_Visa.sql  

---

### 3️⃣ Data Cleaning (SQL + Python)  
- Removed irrelevant columns  
- Handled missing values  
- Standardized data formats  
- Created a cleaned dataset (`h1b_cleaned_data`)  

---

### 4️⃣ Data Analysis (Python)  
- Performed exploratory data analysis (EDA)  
- Analyzed:
  - Case status distribution  
  - Job roles  
  - Wage trends  

---

### 5️⃣ Data Visualization (Power BI)  
- Built an interactive dashboard with KPIs and filters  

---

## 📊 Dashboard Features  

### 🔹 KPI Cards  
- **Total Applications:** 581K  
- **Total Approvals:** 539K  
- **Total Denied:** 3,505  
- **Approval Rate:** 92.91%  

---

### 🔹 Visualizations  
- Application Status Distribution (Donut Chart)  
- Top Job Titles (Bar Chart)  
- Average Wage by Job Role  
- H1B Approval by City  
- Top Employers (Amazon, Cognizant, EY, Microsoft, Google)  
- Map showing application distribution across states  

---

### 🔹 Filters  
- Case Status (Certified, Denied, Withdrawn)  

---

## 🛠 Tools & Technologies  
- **MySQL** → Data storage & querying  
- **Python (Pandas, NumPy)** → Data cleaning & analysis  
- **Power BI** → Dashboard development  
- **DAX** → Calculations & KPIs  
- **Power Query** → Data transformation  

---

## 📈 Key Insights  
- Majority of applications are **Certified (Approved)**  
- High demand for **Software & IT roles**  
- Key hiring locations:
  - New York  
  - Seattle  
  - Austin  
  - San Francisco  
- Top companies dominate sponsorship:
  - Amazon  
  - Cognizant  
  - EY  
  - Microsoft  
- Wage varies significantly by job role and expertise  

---

## 🚀 How to Run the Project  

1. **Setup Database**
   - Run SQL script in MySQL  
   - Import dataset  

2. **Run Python Notebook**
   - Perform cleaning and preprocessing  

3. **Open Power BI**
   - Load cleaned dataset  
   - Open `.pbix` dashboard file  

4. **Explore Dashboard**
   - Use filters and visuals for insights  

---

## 📷 Dashboard Preview  
(Add your dashboard screenshot here)

---

## 🔮 Future Enhancements  
- Add time-based trend analysis  
- Build prediction model for approval chances  
- Improve dashboard UI/UX  
- Automate ETL pipeline  

---

## 💼 Skills Demonstrated  
- Data Cleaning & Transformation  
- SQL & Database Management  
- Python Data Analysis  
- Data Visualization (Power BI)  
- Business Intelligence  

---

## 🤝 Connect  
If you found this project useful, feel free to connect and share your feedback!

---

## ⭐ Acknowledgment  
This project is built for **learning and portfolio purposes**, demonstrating real-world data analytics skills.
