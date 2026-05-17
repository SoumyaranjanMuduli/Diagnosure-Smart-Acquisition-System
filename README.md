# 🩺 Diagnosure — Medical Diagnosis Analysis

> **Excel and Power BI analytics project** analyzing patient diagnosis data — tracking disease prevalence, diagnostic patterns, department load, and treatment outcomes to support clinical decision-making and hospital resource planning.

---

## 📌 Project Overview

**Diagnosure** is a medical data analytics tool designed to give hospitals and clinicians a clear picture of:

- Which diagnoses are most frequent across patient visits?
- How are patients distributed across departments and specialties?
- What are the trends in disease prevalence over time?
- How do age, gender, and other demographics relate to diagnosis type?
- Where are the operational bottlenecks in the diagnostic process?

---

## 🗂️ Repository Structure

```
📦 diagnosure-medical-analysis
 ┣ 📊 Diagnosure.xlsx        # Source data and Excel analysis (334 KB)
 ┣ 📊 Diagnosure.pbix        # Power BI interactive dashboard (351 KB)
 ┗ 📄 README.md
```

---

## 🔧 Tools Used

| Tool | Purpose |
|---|---|
| **Microsoft Excel** | Data entry, cleaning, pivot analysis |
| **Power BI Desktop** | Interactive dashboard and DAX measures |

---

## 📦 Dataset Overview

The dataset contains patient-level diagnostic records with fields including:

| Field | Description |
|---|---|
| `Patient ID` | Unique patient identifier |
| `Age` | Patient age |
| `Gender` | Male / Female / Other |
| `Department` | Medical department (Cardiology, Ortho, General, etc.) |
| `Diagnosis` | Primary diagnosis code / name |
| `Visit Date` | Date of consultation or admission |
| `Test Ordered` | Diagnostic tests requested |
| `Test Result` | Positive / Negative / Inconclusive |
| `Treatment Given` | Treatment or medication prescribed |
| `Follow-up Required` | Yes / No |
| `Outcome` | Recovered / Ongoing / Referred |

---

## 📊 Dashboard Highlights

**KPI Cards**
- Total Patient Records
- Most Common Diagnosis
- % Positive Test Results
- % Requiring Follow-up

**Visuals**
- Top 10 diagnoses by frequency (horizontal bar)
- Patient distribution by department (donut / bar)
- Age group vs. diagnosis type (heatmap / matrix)
- Gender breakdown by diagnosis (grouped bar)
- Monthly visit trend (line chart)
- Test result outcomes by department (stacked bar)
- Follow-up requirement by diagnosis (bar)
- Outcome distribution — Recovered / Ongoing / Referred (donut)

**Slicers**
- Department
- Gender
- Age group
- Date range
- Diagnosis category
- Outcome

---

## 💡 Key Insights

- A small number of diagnoses (top 5) account for the majority of all patient visits — **80/20 pattern** clearly visible
- Certain age groups show a strong concentration in specific diagnoses — valuable for **preventive care targeting**
- Departments with high patient volume don't always show proportionally high follow-up rates — may indicate discharge quality differences
- Inconclusive test results are concentrated in specific departments — potential for **diagnostic process improvement**
- Female and male patients show distinctly different diagnosis distributions across several categories

---

## 🚀 How to Use

1. Open **Power BI Desktop**
2. Load `Diagnosure.xlsx` via **Get Data → Excel**
3. Open `Diagnosure.pbix`
4. Refresh data source if prompted

For Excel analysis only:
- Open `Diagnosure.xlsx` and navigate to the pivot table sheets for pre-built summaries

---

## 👤 Author

**[Your Name]**
[LinkedIn](https://linkedin.com/in/yourprofile) · [Portfolio](https://yourportfolio.com) · [Email](mailto:you@email.com)

---

## 📄 License

MIT License — see [LICENSE](LICENSE) for details.

---

*Patient data is anonymized and used for educational and analytical purposes only.*
