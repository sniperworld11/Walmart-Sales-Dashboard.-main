# 📊 Walmart Sales Dashboard  

An interactive **Power BI Sales Dashboard** designed to provide Walmart’s management and operations teams with **real-time insights** into sales performance, trends, and key metrics across regions, products, and customers.  

🔗 **[View the Dashboard](https://github.com/sniperworld11/Walmart-Sales-Dashboard.-main/blob/main/Walmart-Sales-Dashboard.-main/Screenshot%202024-08-04%20151423.png)**  

---

## 🚀 Problem Statement  

The objective of this project is to build a **comprehensive and interactive sales dashboard** in Power BI that:  
- Enhances **visibility** into sales operations.  
- Provides **real-time insights** into performance, trends, and KPIs.  
- Facilitates **data-driven decision-making**.  
- Identifies **areas of improvement** for Walmart’s business teams.  

---

## ⚙️ Steps Followed  

1. **Data Loading**  
   - Imported CSV dataset into Power BI Desktop.  

2. **Data Profiling**  
   - Used Power Query Editor → Enabled *column distribution, column quality, column profile*.  
   - Changed profiling to run on the **entire dataset** (not just the first 1,000 rows).  

3. **Data Cleaning**  
   - Checked for missing values.  
   - Found null values only in **Delivery Delay** column (<1%). These were ignored for average delay calculation.  

4. **Data Modeling & Transformation**  
   - Created calculated columns and measures.  
   - Grouped customers into **age groups**.  

5. **Dashboard Design**  
   - Applied a theme for consistency.  
   - Added **region-specific slicers** (Central, East, West, South).  
   - Used card visuals for **Average Sales** & **Average Profit**.  
   - Inserted company logo & styled with shapes for clean design.  

6. **Visualizations Added**  
   - Sales & profit trends (time-series).  
   - Regional sales performance.  
   - Product/category breakdown.  
   - Payment methods distribution.  
   - Delivery efficiency analysis.  

---

## 📸 Dashboard Screenshots  

![Dashboard Screenshot](https://github.com/sniperworld11/Walmart-Sales-Dashboard.-main/blob/main/Walmart-Sales-Dashboard.-main/Screenshot%202024-08-04%20151423.png)  
![Screenshot](https://github.com/sniperworld11/Walmart-Sales-Dashboard.-main/blob/main/Walmart-Sales-Dashboard.-main/Screenshot%202024-08-04%20151423.png)  
![Screenshot](https://github.com/sniperworld11/Walmart-Sales-Dashboard.-main/blob/main/Walmart-Sales-Dashboard.-main/Screenshot%202024-08-04%20151440.png)  
![Screenshot](https://github.com/sniperworld11/Walmart-Sales-Dashboard.-main/blob/main/Walmart-Sales-Dashboard.-main/Screenshot%202024-08-04%20151452.png)  
![Screenshot](https://github.com/sniperworld11/Walmart-Sales-Dashboard.-main/blob/main/Walmart-Sales-Dashboard.-main/Screenshot%202024-08-04%20151519.png)  

---

## 🔑 Key Insights  

1. **Annual Sales & Profit**  
   - Total Sales: **$154.9K**  
   - Total Profit: **$21.95K**  
   - Profit Margin: **14.2%**  

2. **Seasonal Trends**  
   - Sales peak in **December** (holiday season).  
   - Profits spike in **April, May, June, December** → strong cost management & high-margin products.  

3. **Regional Performance**  
   - **California** = highest sales & profit.  
   - Central region leads overall performance, followed by West, East, South.  

4. **Payment Methods**  
   - **Online payments** dominate, followed by COD & credit cards.  

5. **Delivery Efficiency**  
   - Average delivery time: **4 days** (efficient logistics).  

6. **Product Performance**  
   - **Phones** = top-selling product.  
   - **Furniture** = leading sales category.  

---

## 🛠️ Tech Stack  

- **Power BI** (Dashboarding & Visualization)  
- **Power Query** (Data Cleaning & Transformation)  
- **DAX** (Measures & Calculations)  
- **SQL** (Data Understanding & Querying)  

---

## 📂 Project Structure  

