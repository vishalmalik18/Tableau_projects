# 📊 Tableau Project — Data Joining & Blending  

This project demonstrates how to **combine multiple data sources** in Tableau using **Inner Join**, **Full Join**, **Cross Join**, and **Data Blending** techniques to analyze **Book Sales**, **Electronic Sales**, and **Total Sales** across different regions and states.  

---

## 1️⃣ Inner Join — Region & State Level Analysis  

### Objective  
Join **Book Sales** and **Electronic Sales** data sources using an **Inner Join**, and display the combined results in a **tabular format**.  

### Insights  
- Displays data where matching states are present in both data sources.  
- Shows **Book Sales**, **Electronic Sales**, and **Total Sales**.  
- Two-level view: *State-wise* and *Region-wise* summaries.  

### Visualization  

#### State-wise Inner Join  
![Inner Join State Level](images/Screenshot%202025-10-30%20142904.png)

#### Region-wise Inner Join  
![Inner Join Region Level](images/Screenshot%202025-10-30%20142917.png)

---

## 2️⃣ Full Join — Area-wise Analysis  

### Objective  
Join **Books** and **Electronics** sheets using a **Full Join** to include all data from both sources and visualize total sales.  

### Insights  
- Displays all records from both data sources, including unmatched states.  
- Shows combined **Electronic**, **Book**, and **Total Sales** in a single line graph.  
- Helps identify areas with missing or mismatched data.  

### Visualization  
![Full Join Area Level](images/Screenshot%202025-10-30%20141751.png)

---

## 3️⃣ Cross Join — State-wise View  

### Objective  
Perform a **Cross Join** to explore every possible pairing between states and categories across the datasets.  

### Insights  
- Displays all possible combinations between data sources.  
- Highlights potential relationships and overlaps.  
- Useful for deep comparative and exploratory analysis.  

### Visualization  
![Cross Join State Level](images/Screenshot%202025-10-30%20150656.png)

---

## 4️⃣ Data Blending — State-wise View  

### Objective  
Blend **Books** and **Electronics** data sources to compare **Book Sales**, **Electronic Sales**, and **Total Sales** on the basis of **State**.  

### Insights  
- Combines aggregated results from multiple sources.  
- Maintains separate data connections while linking key fields.  
- Provides an overall comparison of performance by state.  

### Visualization  
![Data Blending State Level](images/Screenshot%202025-10-30%20154238.png)

---

## 🛠️ Tools Used  

- **Tableau Public** – For building dashboards  
- **Excel** – For data preparation  

---

## 👤 Author  
**Vishal Malik**  
🔗 [LinkedIn](https://www.linkedin.com/in/vishalmalik18/)  
🔗 [GitHub](https://github.com/vishalmalik18)
