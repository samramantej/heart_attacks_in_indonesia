# Heart Attack Analysis in Indonesia  
A Full Data Analysis Project Using Python, SQL (PostgreSQL), and Tableau  

## Project Overview  
This project analyzes factors contributing to heart attacks in Indonesia using a structured data pipeline:  

- **Data Cleaning:** Raw dataset cleaned using Python (Pandas)  
- **Data Analysis:** Insights extracted using SQL (PostgreSQL)  
- **Data Visualization:** Dashboard created in Tableau using PostgreSQL as a data source  

### **Key Goals:**  
- Identify major lifestyle & medical risk factors for heart attacks  
- Compare cases based on age, gender, cholesterol, and income levels  
- Understand regional impact (Urban vs. Rural)  

---

## 1️⃣ Raw Dataset & Cleaning Process  
**Source:** The dataset was provided as a CSV file containing various medical, lifestyle, and demographic features.  

### **Steps Taken in Python (Pandas):**  
- Removed unnecessary columns (e.g., `participated_in_free_screening`)  
- Converted binary values (`0 → No`, `1 → Yes`) for better readability  
- Handled missing values (e.g., `Alcohol Consumption: None → Never`)  
- Exported the cleaned dataset as **`heart_attack_cleaned.csv`**  

📌 **Cleaning (Screenshots)**  
![image](https://github.com/user-attachments/assets/03b98b7e-ea33-4881-a9be-39a12787b91a)
![image](https://github.com/user-attachments/assets/790b345b-cd87-4cb5-bb40-d49b63a213e0)
![image](https://github.com/user-attachments/assets/7c278c39-8454-41e4-9f44-aadff784c2dd)


## 2️⃣ Data Upload & SQL Analysis (PostgreSQL)  
After cleaning, the dataset was uploaded to **PostgreSQL** for structured querying.  

### **Key SQL Queries & Insights:**  
- How many heart attack cases by gender?  
- Which age group is at the highest risk?  
- Impact of cholesterol levels on heart attacks?  
- Do urban or rural regions have more cases?  

📌 **SQL Queries & Results (Screenshots)**  
![image](https://github.com/user-attachments/assets/f6ccfac9-d806-4388-91c5-d219730c0833)
![image](https://github.com/user-attachments/assets/c2af31e9-668b-49bd-9969-577d68a2deb9)



## 3️⃣ Connecting PostgreSQL to Tableau & Creating Dashboard  
The cleaned dataset was directly linked to **Tableau using the PostgreSQL driver** for visualization.  
Instead of exporting a new CSV, a **live connection** was maintained for dynamic updates.  

### **Final Dashboard Includes:**  
- Gender breakdown of heart attacks (**Pie Chart**)  
- Impact of Alcohol & Smoking (**Stacked Bar Chart**)  
- Cholesterol Levels & Risk (**Area Chart**)  
- Urban vs. Rural breakdown by income level (**Stacked Bar Chart**)  

📌 **Final Tableau Dashboard (Screenshots)**  
![image](https://github.com/user-attachments/assets/618d40ce-4338-482b-b946-2ba719be8dbc)


## 📊 Key Findings & Takeaways  
✅ Males had slightly more heart attacks than females.  
✅ People with cholesterol levels between **200-250** were at the highest risk.  
✅ Urban areas had more heart attacks, especially among **low-income individuals**.  
✅ Smoking & Alcohol weren’t strong indicators, but **diet & stress** played a role.  

---

## 🔥 Technologies Used  
✅ **Python** (Pandas) → Data Cleaning  
✅ **PostgreSQL** → SQL Queries & Analysis  
✅ **Tableau** → Data Visualization  
✅ **GitHub** → Project Documentation  

---

## 🚀 Next Steps  
🔹 Fine-tune Tableau dashboard for **more interactivity**  
🔹 Try a **predictive model (Machine Learning)** on this dataset  
🔹 Explore **other similar healthcare datasets**  

---

## 🤝 Let's Connect!  
💼 **LinkedIn:** https://www.linkedin.com/in/mantej-singh-samra-087253326  
📂 **GitHub:** https://github.com/samramantej
📧 **Email:** mantejsamra95@gmail.com
