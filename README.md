#  Uber Project – Power BI Dashboard

### 🔗 [My LinkedIn](https://www.linkedin.com/in/abdulrahman-ahmed66)  
### 📥 [Download the PBIX File](Uber%20project.pbix?raw=true)

---

## 🎥 Project Demo  
<img src="Gif.gif?raw=true" width="1000">

<div align="center">
  <img src="Overview.png?raw=true" alt="Dashboard Banner" width="1000" height="500">
</div>

---

## 📝 Introduction
<details>
  <summary><strong>📌 Overview (click)</strong></summary>

### **Overview**  
> This Power BI project transforms Uber operational data into actionable business intelligence, focusing on **supply-demand dynamics**, **driver performance**, **request fulfillment rates**, and **geographic efficiency**.  
> The dashboard enables stakeholders to identify revenue leakage opportunities and optimize fleet operations through interactive analytics and visual insights.

</details>

<details>
  <summary><strong>📂 Data Sources (click)</strong></summary>

### **Data Sources**  
> The analysis leverages structured Uber operational data capturing the complete ride request lifecycle across multiple dimensions.

**▼ 📑 Data Tables Structure**  
1. **Ride Requests (Fact Table)**
   - `Request ID`, `Driver ID`, `Requests Timestamp`, `Pickup point`, `Status`, `Drop Timestamp`, `Time`

2. **Drivers (Dimension Table)**
   - `Driver ID`, `Driver Name`

</details>

---

## 🎯 Case Study  
This project addresses a real-world scenario where Uber needed an operational analytics dashboard to:
- Monitor ride request fulfillment rates and driver performance  
- Identify supply-demand imbalances across time and locations  
- Analyze root causes of revenue leakage from unfulfilled rides  
- Support strategic decisions on fleet allocation and driver incentives  

---

## 📊 Main KPIs  

| KPI | Value |
|-----|-------|
| 🚗 Total Ride Requests | **6,745** |
| ✅ Completion Rate | **41.97%** |
| ❌ Unfulfillment Rate | **39.29%** |
| ⭐ Top Performing Driver | **Michael Ferguson** |
| 🌍 Geographic Imbalance | **City 52% vs Airport 48%** |
| 🕒 Critical Time Slot | **6 PM - Midnight** |
| 📊 Supply-Demand Gap | **Airport 65% vs City 35%** |

---

## ⚙️ Process
1. Imported and cleaned Uber operational data using Power Query  
2. Built star schema data model with fact and dimension tables  
3. Created DAX measures for Completion Rate and Unfulfillment Rate  
4. Developed time intelligence for hourly/daily trend analysis  
5. Designed interactive dashboards with supply-demand visuals  

---

## 📐 Data Model  
![Data Model](Modling.png?raw=true)

---

## 📈 Dashboard Preview  
<img src="Overview.png?raw=true" width="1000">
<img src="Unfullfillment_Analysis.png?raw=true" width="1000">

---

## 🔍 Key Insights
1. **Revenue Leakage**: 58.03% unfulfillment rate representing 2,914 lost rides and ~$2.8M potential revenue loss
2. **Peak Demand Strain**: 42% unfulfillment on Thursday/Friday evenings (6 PM - midnight)
3. **Geographic Imbalance**: 65% of drivers stationed at Airport despite City generating 52% of requests
4. **Driver Performance Gap**: Average 69.13% completion rate with significant variation among drivers
5. **Supply-Demand Mismatch**: "No Cars Available" (2,650) was primary issue over Cancellations (1,264)

---

## 💡 Conclusion
This Power BI dashboard transforms Uber operations data into actionable intelligence, revealing critical supply-demand gaps and revenue recovery opportunities. By identifying the 58.03% unfulfillment root causes and geographic imbalances, it provides a clear roadmap for optimizing fleet allocation, implementing surge pricing during peak hours, and improving driver performance to capture an estimated $2.8M in potential revenue.

---

## 🧰 Tools Used
- **Power BI Desktop**
- **Power Query**
- **DAX**
- **Data Modeling**
- **Data Visualization**
- **Time Intelligence**
