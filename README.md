# 🧬 Epic Beaker Lab Turnaround Time Analysis

A portfolio project by **Beyonka Powell** — this notebook simulates the work of an Epic Beaker Analyst, using real-world lab data to uncover operational bottlenecks and performance gaps in turnaround time (TAT).

---

## 📁 Project Structure

```
Epic-Lab-Turnaround-Analysis/
├── Data/
│   └── Epic_Beaker_Mock_Data.csv
├── Visuals/
│   ├── avg_tat_by_test_type.png
│   ├── tat_distribution_by_dept.png
│   ├── avg_tat_by_hour.png
│   ├── tests_by_department.png
│   ├── avg_tat_by_tech.png
│   ├── sla_breach_rate.png
│   ├── tat_trend_over_time.png
│   ├── dept_vs_testtype_heatmap.png
│   └── order_collect_result_delays.png
├── Epic_Lab_Analysis.ipynb
├── Epic_Lab_Analysis.html
└── README.md
```

---

## 🎯 Project Goals

* Simulate Epic-style TAT reporting for lab workflows.
* Detect high-risk delays by department and test type.
* Uncover SLA breaches (TAT > 120 min) and root causes.
* Present insights visually for stakeholders.

---

## 📊 Key Visualizations

1. **Bar Chart**: Avg Turnaround Time by Test Type
2. **Box Plot**: TAT Distribution by Department
3. **Heatmap**: Avg TAT by Hour of Day
4. **Pie Chart**: % of Tests by Department
5. **Bar Chart**: Avg TAT by Lab Tech
6. **Pie Chart**: SLA Breach Rate
7. **Line Chart**: TAT Trends Over Time
8. **Heatmap**: Dept x Test Type Avg TAT
9. **Bar Chart**: Delays from Order → Collection → Result

---

## 🧠 Insights Discovered

* **CMP** and **PT/INR** tests have the slowest turnaround.
* **Night shifts (2AM–6AM)** consistently show increased delay.
* **ICU and ER** generate the highest volume of lab orders.
* Over **30% of labs breached SLA**, needing immediate review.
* **Post-collection delay** is the largest contributor to slow TAT.

---

## 💻 Tools Used

* Python 3 (Pandas, Matplotlib, Seaborn)
* Visual Studio Code
* Git/GitHub for version control

---

## 👩🏽‍⚕️ About the Author

**Beyonka Powell** is a Medical Lab Technologist transitioning into Data Analytics. This project merges her lab experience with data-driven storytelling and analysis.

---

## 📬 Contact

* LinkedIn: [www.linkedin.com/in/beyonkapowell0405]
* Email: \[[beyonkap1986@gmail.com]
---
