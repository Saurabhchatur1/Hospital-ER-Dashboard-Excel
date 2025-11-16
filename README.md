# Hospital-ER-Dashboard-Excel
End-to-end Excel dashboard project analyzing hospital emergency room performance with KPIs, patient analytics, and interactive charts.
# 🏥 Hospital Emergency Room Analysis Dashboard (Excel Project)

This project is an **End-to-End Excel Dashboard** designed to analyze **Emergency Room (ER) performance**, improve decision-making, and provide insights into hospital operations.  
The dashboard includes **KPIs, charts, slicers, and dynamic visualizations**, built entirely using **Microsoft Excel**.

📌 **Project Purpose**

The main aim of this project is to help hospital administrators:

- Monitor patient flow and emergency workload  
- Understand patient demographics  
- Measure service efficiency  
- Identify improvement areas  
- Take data-driven decisions

This dashboard provides clear, actionable visual insights for better management of hospital emergency services.


📊 **Key Insights in the Dashboard**

✔ **KPIs Displayed**
- Total Patients  
- % Patients attended within 30 minutes  
- % Delayed patients  
- Number of admitted vs. non-admitted patients  
- Gender-wise patient count  

 ✔ **Charts Included**
- **Patient Admission Status** (Donut/Bar Chart)  
- **Patient Age Distribution** (Histogram or Bar Chart)  
- **Timeliness Performance** (Within 30 min vs Delayed)  
- **Gender Distribution**  
- **Department Referrals** (Most visited departments)  

---

🧮 **Important Formulas Used**

**📌 Power Query – Calendar Table Formula**
Used for date-based analysis:

```text
= List.Dates(#date(2023,01,01), 731, #duration(1,0,0,0))

## 📷 Dashboard Preview

![Dashboard Screenshot](images/Final Dashboard.png)

