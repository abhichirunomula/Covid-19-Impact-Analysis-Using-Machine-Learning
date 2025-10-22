# Covid-19-Impact-Analysis-Using-Machine-Learning
This project analyzes the impact of COVID-19 across countries by comparing health, social, and economic indicators such as HDI, GDP, Stringency Index, and population.  
Visualizations are created using **Plotly** for interactive analysis.
## 🎯 Objectives
- To analyze the relationship between **HDI (Human Development Index)**, **Stringency Index**, and **COVID-19 cases/deaths**.
- To compare **GDP levels before and after COVID-19** across multiple countries.
- To identify the **most affected nations** using statistical aggregation.
- To develop a **Linear Regression model** predicting the economic impact (e.g., GDP drop or case growth).
- To visualize insights using **interactive charts** and correlation heatmaps.

## 📊 Datasets Used
- **raw_data.csv** — Contains COVID-19 case and death data by country.
- **transformed_data.csv** — Contains preprocessed socio-economic indicators.
## ⚙️ Features
- Aggregation of country-level COVID-19 statistics.
- Comparison of GDP before and after COVID-19.
- Visual analysis of:
  - Top 10 countries with highest COVID-19 cases.
  - Creates interactive visualizations using Plotly (px and go) — including bar charts, pie charts, and HDI coloured plots.
  - Computes correlation heatmap (seaborn) and uses a Linear Regression pipeline (train/test split, fit, predict) with evaluation metrics (MAE, MSE, R²).
  - Compares GDP before and after COVID for multiple countries (so the project mixes health and economic analysis).
  - Clustering: cluster countries by multi-metric impact (cases per capita, GDP drop, HDI) to identify similar response groups.
  - Impact of Stringency Index on total cases.
## 🧠 Technologies Used
- Programming Language: Python 3.x 
- Data Analysis: Pandas, NumPy.
- Visualization: Plotly Express, Plotly Graph Objects, Seaborn, Matplotlib. 
- Machine Learning: Scikit-learn (LinearRegression, train_test_split, metrics) .
- Environment: Jupyter Notebook, Google Colab. 


