# 📊 Sales & Profit Analysis – Global Superstore
This project analyzes the **Global Superstore dataset** using Microsoft Excel and Python. The goal is to understand sales and profit trends across different regions and product categories and to build visual dashboards using both tools.

---

## ✅ Tools Used

- **Microsoft Excel**  
  (PivotTables, Charts, Slicers, Conditional Formatting)
- **Python (Google Colab)**  
  Libraries: `pandas`, `matplotlib`

---

## 📂 Project Files

- Excel Sheet(https://docs.google.com/spreadsheets/d/1KB8C2_L1fmaTPsddzeG60Enl62bMyGIY/edit?usp=sharing&ouid=103321712003141092161&rtpof=true&sd=true).
- 📄 [Project Report (PDF)](https://drive.google.com/file/d/1QE44P48bJ_4MieHbRNi4Zba4Z7VI-v0Y/view?usp=sharing)
- 📊 [Excel Dashboard File (Google Drive)](https://docs.google.com/spreadsheets/d/1MSqbVZuFZPAJabS8s1Dy1CYTKp3K6yDo/edit?usp=sharing&ouid=103321712003141092161&rtpof=true&sd=true)
- 🐍 [Python Notebook (.ipynb)](https://colab.research.google.com/drive/1C9Q8pdjJRAkkgeixUcQknWShLuXgbGKl?usp=sharing) *(if uploaded)*

---

## 🔍 Key Features

- Region-wise and Category-wise Profit Analysis
- Interactive Excel dashboard with slicers and charts
- Python analysis using `groupby()` and `matplotlib`
- Bar and Pie charts recreated using Python
- Insights and future recommendations section

---

## 📈 Sample Python Output

```python
# Grouping by Region
region_profit = df.groupby("Region")["Profit"].sum()

# Bar Chart
region_profit.plot(kind='bar')
plt.title("Profit by Region")
