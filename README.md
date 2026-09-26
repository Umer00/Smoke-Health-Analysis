# 🚬 Smoke Health Analysis

> **An interactive Power BI dashboard for exploring the relationship between smoking behavior, patient health factors, and organ conditions.**

![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-F2C811?style=for-the-badge\&logo=powerbi\&logoColor=black)
![Data Analysis](https://img.shields.io/badge/Data%20Analysis-Healthcare-0F766E?style=for-the-badge)
![Healthcare Analytics](https://img.shields.io/badge/Domain-Healthcare-2563EB?style=for-the-badge)

---

## 📌 Overview

**Smoke Health Analysis** is an interactive healthcare analytics project built with **Microsoft Power BI** to explore how smoking-related behavior and patient health factors relate to organ conditions.

The dashboard transforms raw patient data into an interactive analytical experience using **data modeling, calculated measures, slicers, visualizations, and dynamic organ-condition images**.

The project is designed to demonstrate how healthcare data can be transformed into meaningful visual insights that are easier to explore, compare, and communicate.

---

## 🎯 Project Objectives

The main objectives of this project are to:

* Analyze patient health and smoking-related information.
* Explore relationships between smoking behavior and organ conditions.
* Compare patient groups using demographic and health-related factors.
* Identify patterns across different organ conditions.
* Provide interactive filtering for deeper analysis.
* Use dynamic visuals to represent healthy and affected organs.
* Build a clean and interactive healthcare analytics dashboard.

---

## 📊 Dashboard Features

### 🔹 Interactive Analysis

The dashboard allows users to explore the dataset dynamically through interactive filters and visualizations.

### 🔹 Patient Health Analysis

Explore patient-level health information and identify patterns across different health-related variables.

### 🔹 Smoking Analysis

Analyze smoking-related characteristics and investigate how smoking behavior varies across patient groups.

### 🔹 Organ Condition Analysis

Compare different organ conditions and explore the distribution of healthy and affected organs.

### 🔹 Dynamic Organ Visualization

The project includes an **Organ Images** dataset containing:

| Field       | Description                  |
| ----------- | ---------------------------- |
| `Organ`     | Name of the organ            |
| `Condition` | Organ health condition       |
| `ImageURL`  | Image used for visualization |

This enables the dashboard to dynamically display an organ image based on the selected organ and condition.

---

## 🧩 Data Model

The project uses a Power BI data model to connect patient health information with organ-related visualization data.

### Main Components

```text
Patient Health Dataset
        │
        ├── Patient Information
        ├── Smoking Information
        ├── Health Factors
        └── Organ Condition
                 │
                 ▼
          Organ Images Table
                 │
                 ├── Organ
                 ├── Condition
                 └── ImageURL
```

This structure allows dashboard selections to dynamically control the displayed organ visualization.

---

## 🛠️ Tools & Technologies

| Technology             | Purpose                                      |
| ---------------------- | -------------------------------------------- |
| **Microsoft Power BI** | Dashboard development & visualization        |
| **Power Query**        | Data preparation & transformation            |
| **DAX**                | Calculated measures and dynamic logic        |
| **CSV**                | Dataset and organ-image mapping              |
| **Data Modeling**      | Connecting analytical and visualization data |

---

## 📁 Repository Structure

```text
Smoke-Health-Analysis/
│
├── 📂 Organ_Images/
│   ├── Healthy organ images
│   └── Condition-specific organ images
│
├── 📄 Organ_Images.csv
│
├── 📄 updated_retail_sales_dataset.csv
│
├── 📊 smoking_health_analysis_dashboard.pbix
│
└── 📖 README.md
```

> **Note:** The `.pbix` file contains the main Power BI dashboard and can be opened using **Microsoft Power BI Desktop**.

---

## 🔄 Analysis Workflow

The project follows a typical data analytics workflow:

```text
Raw Data
   ↓
Data Preparation
   ↓
Data Modeling
   ↓
DAX Measures
   ↓
Interactive Visualizations
   ↓
Dynamic Organ Visualization
   ↓
Healthcare Insights
```

---

## 💡 Key Analytical Areas

The dashboard focuses on several areas of healthcare analysis:

### 👤 Patient Demographics

Analysis of patient characteristics and demographic distributions.

### 🚬 Smoking Behavior

Exploration of smoking-related characteristics and patterns.

### ❤️ Organ Health

Comparison of organ conditions across different patient groups.

### 🩺 Health Risk Factors

Investigation of health-related variables that may be associated with different organ conditions.

### 📈 Interactive Exploration

Users can apply filters and slicers to explore specific segments of the dataset.

---

## 🖼️ Dashboard Preview

Add your final dashboard screenshot below to make the repository more visually attractive:

```markdown
![Smoke Health Analysis Dashboard](dashboard-preview.png)
```

You can also create a `screenshots` folder:

```text
screenshots/
└── dashboard-preview.png
```

and use:

```markdown
![Dashboard Preview](screenshots/dashboard-preview.png)
```

---

## 🚀 How to Use

### 1. Clone the Repository

```bash
git clone https://github.com/Umer00/Smoke-Health-Analysis.git
```

### 2. Open the Project

Open:

```text
smoking_health_analysis_dashboard.pbix
```

using **Microsoft Power BI Desktop**.

### 3. Explore the Dashboard

Use the available filters, slicers, charts, and visualizations to explore the patient health and smoking-related data.

---

## 📌 Project Highlights

* 📊 Interactive Power BI dashboard
* 🚬 Smoking-related healthcare analysis
* 🩺 Organ condition analysis
* 🔗 Relational data modeling
* 🧮 DAX-based calculations
* 🧹 Data transformation with Power Query
* 🖼️ Dynamic organ-condition visualization
* 🎛️ Interactive filtering and exploration
* 📈 Data-driven healthcare storytelling

---

## 🎓 Skills Demonstrated

This project demonstrates practical experience with:

* **Data Analysis**
* **Data Cleaning**
* **Data Transformation**
* **Data Modeling**
* **Power Query**
* **DAX**
* **Data Visualization**
* **Dashboard Design**
* **Healthcare Analytics**
* **Interactive Reporting**
* **Analytical Storytelling**

---

## ⚠️ Disclaimer

This project is intended for **data analytics and visualization purposes only**.

The analysis should not be interpreted as medical advice, clinical diagnosis, or a substitute for professional medical research.

---

## 👨‍💻 Author

**Umer**

Aspiring **Data Analyst / Data Scientist**

📌 GitHub:
https://github.com/Umer00

---

## ⭐ If you find this project useful

Feel free to **star ⭐ the repository** and explore the other data analytics projects on my GitHub.
