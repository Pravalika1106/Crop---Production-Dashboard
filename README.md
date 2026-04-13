# 📊 Crop Production Analysis Dashboard (Power BI)

## 📌 Project Overview
This project presents an interactive **Power BI dashboard** built using a real-world dataset from **data.gov.in**, focusing on district-wise crop production across India.

The dashboard provides insights into agricultural production patterns, efficiency, seasonal trends, and geographic distribution to support better understanding of resource utilization and productivity.

---

## 🎯 Objectives
The main objectives of this project are:

- Analyze overall crop production trends over time  
- Identify top-performing states and regions  
- Understand seasonal contribution to production  
- Evaluate land utilization vs production output  
- Measure agricultural efficiency using yield  
- Visualize geographic distribution of production  
- Analyze growth patterns and ranking changes  

---

## 📂 Dataset Information
- **Source:** data.gov.in  
- **Type:** District-wise crop production data  

### Key Columns:
- State  
- District  
- Year  
- Season  
- Crop  
- Area  
- Production  

---

## 🧹 Data Cleaning & Transformation
Data preprocessing was performed using **Power Query Editor**:

- Removed null and invalid values  
- Eliminated duplicate records  
- Standardized text formatting (state, crop, season)  
- Fixed inconsistent category names  
- Applied correct data types  

### ➕ Additional Columns Created:
- **Yield** = Production / Area  
- **Production Category** (High / Medium / Low)  
- **Area Category** (Large / Medium / Small)  
- **Efficiency Flag** (High / Average / Low Efficiency)  
- **Season Sort Column** (for proper ordering)  

---

## 📐 Data Modeling & DAX Measures

The following measures were created using DAX:

- Total Production  
- Total Area  
- Average Yield  
- Production Growth %  
- Previous Year Production  
- State Ranking  
- Total Districts  
- Total Crops  
- Most Efficient State  
- Highest Yield Crop  

---

## 📊 Dashboard Structure

The dashboard is divided into three pages:

---

### 🔹 Page 1: Overview & Trends
Provides a high-level summary of agricultural production.

**Visuals Included:**
- KPI Cards (Total Production, Area, Yield, Growth %)  
- Bar Chart → Top Producing States  
- Line Chart → Production Trend Over Years  
- Donut Chart → Season-wise Contribution  
- Treemap → Crop Contribution  

---

### 🔹 Page 2: Efficiency & Resource Analysis
Focuses on how efficiently land is used for production.

**Visuals Included:**
- Clustered Column Chart → Area vs Production  
- Scatter Plot → Yield Analysis  
- Bubble Chart → Efficiency Gap Identification  
- KPI Cards (Efficiency Metrics)  

---

### 🔹 Page 3: Geography & Growth Insights
Highlights spatial and growth-based insights.

**Visuals Included:**
- Map → Geographic Distribution of Production  
- Waterfall Chart → Growth Momentum  
- Ribbon Chart → Rank Dynamics of States  
- Insight Panel  

---

## 🔍 Key Insights

- A few states contribute a significant portion of total production  
- Seasonal patterns (Kharif & Rabi) strongly influence output  
- Some regions show high land usage but low productivity  
- Agricultural efficiency varies across crops and regions  
- Production trends show periods of growth and decline over time  

---

## 🛠 Tools & Technologies Used

- **Power BI** → Dashboard Development  
- **Power Query** → Data Cleaning & Transformation  
- **DAX** → Data Modeling & Calculations  

---

## 🎯 Learning Outcomes

Through this project, I gained experience in:

- Data cleaning and transformation  
- Building interactive dashboards  
- Writing DAX measures  
- Designing effective visualizations  
- Extracting insights from real-world data  

---

## 📸 Dashboard Preview

_Add your dashboard screenshots here_

Example: