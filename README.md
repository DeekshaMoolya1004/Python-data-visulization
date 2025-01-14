# Python-data-visulization
# 📊 Education and Employment Data Visualization 🚀

## 📌 Overview  
This project explores **Employment Rates and Salary Trends** across various states using **Python, Pandas, Matplotlib, and Seaborn**. 📈📉  
It provides **meaningful insights** by visualizing the data in different ways to understand **employment patterns, salary growth, and correlations**.  

---

## 🛠️ Data Cleaning Process  
Before visualizing the data, we applied essential **data cleaning techniques** to ensure accuracy.  

✔ **Load Dataset** from an **Excel file**.  
✔ **Check first and last records** using:  
   ```python
   df.head()  # First 5 rows
   df.tail()  # Last 5 rows
   ```
✔ **Check for missing values**:  
   ```python
   df.isnull().sum()  # Count missing values
   df.dropna(inplace=True)  # Remove missing values
   ```
✔ **Remove Duplicates**:  
   ```python
   df.duplicated().sum()  # Count duplicate rows
   df.drop_duplicates(inplace=True)  # Remove duplicates
   ```
✔ **Convert Data Types (if needed)**:  
   ```python
   df['Salary'] = df['Salary'].astype(float)  # Ensure Salary is float
   df['Year'] = pd.to_numeric(df['Year'], errors='coerce')  # Convert Year to numeric
   ```
✔ **Check Data Summary**:  
   ```python
   df.info()  # Display dataset information
   df.describe()  # Show statistical summary
   ```

**🔹 After cleaning, the dataset is accurate and ready for visualization! 🎯**  

---

## 🎨 Visualizations Included  
🔹 **Pie Chart** - Employment Rate Distribution 🥧  
🔹 **Bar Chart** - Employment Rate by State 📊  
🔹 **Horizontal Bar Chart** - Easy comparison of employment rates ↔️  
🔹 **Line Chart** - Salary trends over time 📈  
🔹 **Scatter Plot** - Relationship between Salary & Employment 💰  
🔹 **Histogram** - Salary distribution 📦  
🔹 **Area Chart** - Employment rate growth 🌍  

Each graph provides a **unique perspective** on the dataset, making it easier to **analyze and interpret key trends**! 🚀  

---

## 🔧 Technologies Used  
✅ **Python** 🐍  
✅ **Pandas** 📊  
✅ **Matplotlib** 🎨  
✅ **Seaborn** 🌊  
✅ **Google Colab** 💻  


## 🎯 Key Insights  
✅ Employment rates **vary significantly** across states.  
✅ **Higher employment rates may not always mean higher salaries**.  
✅ Salary trends **show gradual growth** over the years.  
✅ Heatmap analysis reveals **strong correlations** between key factors.  
