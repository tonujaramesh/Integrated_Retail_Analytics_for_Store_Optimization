# Integrated Retail Analytics for Store Optimization

📌**Project Overview**  

This project applies Exploratory Data Analysis and Machine Learning to retail sales data from multiple stores. By integrating store attributes, promotions, and external factors (temperature, fuel price, CPI, unemployment), it predicts weekly sales, uncovers trends, and provides insights for store optimization.

📂 **Dataset Description**

This project has three datasets:

1️⃣ **Sales Dataset (421k rows × 5 cols)**

Weekly sales per store & department.

Columns: Store, Dept, Date, Weekly_Sales, IsHoliday.

2️⃣ **Stores Dataset (45 rows × 3 cols)**

Store metadata.

Columns: Store, Type, Size.

3️⃣ **Features Dataset (8k rows × 12 cols)**

External economic & promotional factors.

Columns: Store, Date, Temperature, Fuel_Price, MarkDown1-5, CPI, Unemployment, IsHoliday

📊 **Visualizations & Insights**

✅ Histogram – Weekly sales distribution → Most sales are in lower range; few weeks have extreme sales spikes.

✅ Box & Bar Plots – Sales by store type → Larger stores (Type A) dominate sales.

✅ Line Plot – Sales trend → Seasonal peaks around holidays 🎉.

✅ Heatmap – Correlation between features → Weak economic links, markdowns impact sales modestly.

✅ Scatter Plots – Sales vs temperature/fuel price → Weak to moderate effects.

✅ Holiday vs Non-Holiday – Holiday weeks nearly double sales.

✅ Rolling Average – Long-term seasonal trends become visible.

🛠 **Tech Stack**

Language: Python 🐍

Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

IDE/Notebook: Jupyter Notebook 📓

Visualization: Matplotlib & Seaborn 📊

Modeling: Regression Models 📈

🏁 **Conclusion**

🔹 Holidays, store size, and promotions are major drivers of sales.

🔹 Economic factors (fuel, CPI, unemployment) have smaller but noticeable impacts.

🔹 ML models achieve good predictive accuracy, helping in demand forecasting 📈.

🔹 This analysis enables inventory optimization, strategic planning, and revenue growth in retail.
