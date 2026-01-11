# 🧠 Workplace Mental Health Visualization Project (Pandas & Matplotlib)

## 📌 Project Overview

This project analyzes a **real-world workplace mental health survey dataset** using **Python (Pandas & Matplotlib)** to understand how demographic and workplace factors influence employee mental well-being. The goal is to convert raw survey data into **clear, meaningful visual insights** that help organizations and individuals better understand mental health trends in the workplace.

---

## 🎯 Objectives

* Analyze workplace mental health survey data
* Identify key factors affecting employee mental health
* Create insightful data visualizations using Matplotlib
* Highlight how work environment and demographics influence treatment-seeking behavior

---

## 📊 Dataset Description

The dataset contains responses from employees across different countries and industries. It includes information about demographics, work environment, company policies, and mental health outcomes.

### Key Features

* **Demographic:** `Age`, `Gender`, `Country`, `state`
* **Employment Type:** `self_employed`, `no_employees`, `remote_work`, `tech_company`
* **Mental Health Background:** `family_history`, `treatment`, `work_interfere`
* **Company Policies & Support:** `benefits`, `care_options`, `wellness_program`, `seek_help`, `anonymity`, `leave`
* **Workplace Attitude:** `coworkers`, `supervisor`, `mental_health_interview`, `phys_health_interview`, `mental_vs_physical`
* **Impact & Consequences:** `mental_health_consequence`, `phys_health_consequence`, `obs_consequence`

### 🎯 Target Variable

**`treatment`** – Indicates whether an employee has sought treatment for a mental health condition. This is the primary outcome used to analyze how workplace and demographic factors influence mental health support-seeking behavior.

---

## ⚙️ Technologies Used

* **Python** 🐍
* **Pandas** – Data cleaning and analysis
* **Matplotlib** – Data visualization
* **NumPy** – Numerical operations
* **Jupyter Notebook** – Analysis environment
* **Git & GitHub** – Version control

---

## 📈 Visualizations Created

The following visualizations were generated to understand mental health patterns in the workplace:

1. **Gender Distribution (Bar Chart)** – Shows respondent distribution across genders
2. **Treatment Proportion (Pie Chart)** – Displays percentage of employees who sought treatment
3. **Age Distribution (Histogram)** – Shows age spread of respondents
4. **Age vs Treatment (Boxplot)** – Compares age of employees who sought vs did not seek treatment
5. **Company Size vs Treatment (Bar Chart)** – Shows effect of company size on treatment-seeking
6. **Remote Work vs Treatment (Bar Chart)** – Analyzes influence of remote work
7. **Work Interference vs Treatment (Bar Chart)** – Shows how mental health affects work
8. **Combined View (Subplots)** – Multiple plots in one view for overall insight

---

## 🔄 Project Workflow

1. Load and explore the dataset
2. Clean and preprocess data using Pandas
3. Perform exploratory data analysis (EDA)
4. Create visualizations using Matplotlib
5. Interpret trends and draw conclusions

---

## 📁 Project Structure

```
Workplace-Mental-Health-Visualization/
│
├── data/
│   └── survey.csv
├── notebooks/
│   └── work.ipynb
├── images/
│   └── visualizations.png
└── README.md
```

---

## ▶️ How to Run the Project

1. Clone the repository

   ```bash
   git clone https://github.com/your-username/Workplace-Mental-Health-Visualization.git
   ```
2. Navigate to the project folder

   ```bash
   cd Workplace-Mental-Health-Visualization
   ```
3. Install required libraries

   ```bash
   pip install pandas matplotlib numpy
   ```
4. Open the Jupyter Notebook

   ```bash
   jupyter notebook
   ```
5. Run all cells in `work.ipynb` to generate the analysis and plots

---

## 🧠 Key Insights

* Mental health issues affect employees across all age groups
* Many employees hesitate to seek treatment due to workplace stigma
* Supportive company policies improve treatment-seeking behavior
* Remote work and company size influence mental health outcomes
* Work interference strongly correlates with mental health treatment

---

## 🔮 Future Enhancements

* Add interactive dashboards (Streamlit or Power BI)
* Use Seaborn for enhanced visuals
* Apply machine learning for mental health risk prediction
* Expand the dataset for deeper analysis

---

## 👤 Author

**Bhavya Das**
B.Tech 




