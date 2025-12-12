# Welcome to My GitHub Portfolio! ✨ 

This repository showcases a selection of projects where I have applied data analysis and data science to solve real-world problems. My passion lies in transforming data into actionable insights and building robust, user-friendly applications. 

---

## Technical Toolkit 🛠️

My projects demonstrate proficiency in:

*	**Programming Languages:** Python, SQL, HTML
*	**Frameworks:** Pandas, Numpy, Matplotlib, Seaborn, TensorFlow, Scikit-Learn, FastAPI, Plotly Dash, Ngrok, Docker
*	**Databases:** MongoDB, MySQL, SQLite, ChromaDB
*	**Tools:** Microsoft Excel, PowerPoint, PowerBI, Jupyter Notebook, Google Colab, Kaggle Notebook, Github
*	**Soft Skills:** Strategic Problem-Solving, Synergistic Collaboration, Excellent Time Management, Articulate Communication 


---

## Projects 💻

### 1. [Stock Volatility Forecasting System](https://github.com/Obika-Franklin/StockAnalysisAPI) 

**Problem:** Financial markets demand tools for risk assessment and informed decision-making.

**Solution:** Developed a comprehensive system for predicting stock volatility. This project utilizes a **GARCH model** for forecasting, powered by a **FastAPI** backend for model training and prediction. The system integrates **Alpha Vantage API** for real-time data, stores historical data in **SQLite**, and provides model persistence with `joblib`. A user-friendly web interface built with **Plotly Dash** enables interactive analysis and real-time use.

**Impact:** Provides valuable insights for investors, supports risk management strategies, and can be integrated into automated trading systems. 

---

### 2. [Impact of Reminder Emails on Admissions Exam Completion Rates (A/B Testing)](https://github.com/Obika-Franklin/HypothesisTesting/tree/main) 

**Problem:** Low conversion of user registrations to exam completions in online learning platforms.

**Solution:** Conducted a controlled **A/B test** using synthetic data to evaluate the effectiveness of reminder emails on admissions exam completion rates. The analysis is presented through an interactive web application built with **Plotly Dash**, allowing stakeholders to visualize key metrics and understand the impact of behavioral nudges.

**Impact:** Delivers data-driven insights to enhance user engagement and improve conversion rates in digital education platforms. 

---

### 3. [Understanding Credit Insecurity: A Data-Driven Segmentation of American Households](https://github.com/Obika-Franklin/CreditInsecurityAnalysis) 

**Problem:** Identifying and understanding households facing credit insecurity.

**Solution:** Applied unsupervised machine learning (**K-Means Clustering**) to the 2022 U.S. Federal Reserve's **Survey of Consumer Finances (SCF)** data. Used **Principal Component Analysis (PCA)** for dimensionality reduction to identify distinct segments of credit-constrained households. The insights are presented through a dynamic web-based dashboard developed with **Plotly Dash**.

**Impact:** Provides valuable insights for marketing, public policy, and financial services to better understand and address credit insecurity. 

---

### 4. [Predicting Structural Damage Post-Earthquake in Kavrepalanchok, Nepal](https://github.com/Obika-Franklin/BuildingDamageAnalysis/tree/main) 

**Problem:** The critical need to predict building damage from earthquakes for proactive disaster preparedness.

**Solution:** Developed a predictive model to identify buildings prone to severe damage *before* an earthquake. This project involved collecting detailed building characteristics into a **SQLite database**. Overcame dataset imbalance using **SMOTE** and **Random Undersampling** techniques, and trained a tuned **Random Forest classifier** for improved accuracy in identifying vulnerable structures.

**Impact:** Enables proactive reinforcement and targeted aid distribution, significantly enhancing community resilience in earthquake-prone regions. 

---

### 5. [STOCK ANALYSIS CHATBOT](https://github.com/Obika-Franklin/StockAnalysisChatbot/tree/main) 

**Problem:** Navigating the complexities of stock market information can be challenging for many.

**Solution:** Built an intelligent stock analysis chatbot designed to make market insights accessible and understandable. This Python project fetches real-time or historical stock data using the **Alpha Vantage API**, analyzes trends, and calculates technical indicators (e.g., SMA, RSI). Analyzed data is stored and retrieved from a **ChromaDB** instance, enabling **Retrieval-Augmented Generation (RAG)** to provide contextually relevant answers using a **Gemini language model**. The chatbot handles queries for single or multiple stocks and includes an evaluation mechanism for response quality.

**Impact:** Empowers users, regardless of technical expertise, to gain insights into stock market trends and key indicators through natural language interaction. 

---
### 6. [Weather Data Analysis of Six Global Cities in 2014](https://github.com/Obika-Franklin/Weather-Data-Analysis)

This project involves a comprehensive analysis of weather data collected throughout 2014 for six diverse global cities: Beijing, Brasilia, Cape Town, Delhi, London, and Moscow. By examining key meteorological parameters such as temperature, precipitation, humidity, dew point, and wind speed, we aim to uncover distinct climatic patterns, assess thermal stability, characterize precipitation regimes, understand the relationship between humidity and dew point, analyze seasonal temperature variations, and evaluate wind speed characteristics across these different geographical locations. This comparative analysis provides insights into the varied climates experienced around the world and highlights notable differences and similarities in their weather behaviors during the year 2014.

---

### 7. [Data-Driven Selection of Favorable Summer Holiday Weeks Based on London Heathrow Weather Patterns](https://github.com/Obika-Franklin/London_Heathrow_Weather_Analysis/tree/main)
This project aimed to identify the best two-week period for a summer holiday in 2023 based on historical weather data for London Heathrow. By analyzing various weather metrics such as temperature, precipitation, sunshine duration, and wind speed, a scoring system was developed to rank the weeks of the summer season. The goal was to leverage data analysis techniques to provide insights into favorable weather patterns and recommend optimal holiday dates.

---

### 8. [Inflow Performance Relationship (IPR) Modeling and Sensitivity Analysis in Excel](https://github.com/Obika-Franklin/IPR-Modeling-and-Sensitivity-Analysis-in-Excel)
In this project, I developed a comprehensive, Excel-based methodology to model and analyze the Inflow Performance Relationship (IPR) for oil wells across different flow regimes. Specifically, I calculated and graphed the IPR for both linear (undersaturated) reservoirs (which follow Darcy's law) and non-linear (saturated/two-phase) reservoirs using industry-standard empirical correlations. For the linear regime, I demonstrated the impact of key variables, such as the skin factor, production time, and reservoir depletion, on the IPR curve. For the non-linear IPR, I carried out a comparative analysis between the Vogel and Fetkovich IPR equations, highlighting their differences in predicting the well's maximum potential (Absolute Open Flow or AOF) and determining which model is more reliable for real-world application using field test points.

---

### 9. [Exponential Decline Modeling and Production Forecasting (DCA)](https://github.com/Obika-Franklin/Exponential-Decline-Modeling-and-Production-Forecasting-DCA)
In this project, I performed a Decline Curve Analysis (DCA) on historical production data from an onshore field to predict future production rates and estimate the field's economic lifespan. This empirical method is one of the most widely used techniques in petroleum engineering for estimating recoverable reserves. The goal was to provide a critical forecast of the field's remaining economic life and total recoverable reserves, which is essential for guiding investment and production planning.

---

### 10. [Comparative Analysis of Global Socio-Economic Indicators (2013)](https://github.com/Obika-Franklin/Comparative-Analysis-of-Global-Socio-Economic-Indicators-2013/tree/main)
In this project, I performed a comparative analysis of global socio-economic indicators from 2013. The analysis utilized data retrieved from the World Bank's development indicators API, focusing on a set of key metrics including total Gross Domestic Product (GDP), GDP per capita, total population, life expectancy, the Gini index, and the unemployment rate. Before the analysis, I conducted data cleaning and preprocessing, which involved handling missing values, filtering out non-country aggregate entries, and performing unit conversions and feature engineering (specifically computing GDP per capita). The primary goal of the study was to shed light on the complex factors that contribute to a nation's overall well-being by examining the interrelationships between these various indicators.

---

### 11. [Trade Flow Analysis: Nigeria’s Cocoa (2023) & UK's Milk (2014) Markets](https://github.com/Obika-Franklin/Trade_Analysis_Nigeria_and_UK/tree/main)
In this project, I conducted an in-depth analysis of international trade data using Python’s pandas library to uncover trade patterns, identify key partners, and explore seasonal trends. The data, sourced from the United Nations Comtrade Database, focused on two case studies: Nigeria’s cocoa trade in 2023 (commodity codes 1801 and 1802) and the United Kingdom’s milk trade in 2014 (commodity code 0402). Through data cleaning, transformation, aggregation, and pivot table analysis, I examined trade balances, major trading partners, and temporal dynamics to derive clear and actionable insights from these commodity markets.

---

### 12. [Step-by-Step PVT Analysis for Reservoir Engineering and Excel Application](https://github.com/Obika-Franklin/PVT_Analysis_For_Reservoir_Engineering/tree/main)

This project successfully demonstrated the fundamental process of converting laboratory Pressure-Volume-Temperature (PVT) data, specifically from the differential liberation experiment, into field-ready parameters, addressing Exercise 2.2 from L. P. Dake’s Fundamentals of Reservoir Engineering textbook. The analysis commenced by identifying the optimum surface separation conditions from surface separator tests, which was critical for establishing the necessary correction factors, the Shrinkage Factor ($c_{bf}$) and the Initial Solution Gas-Oil Ratio ($R_{sif}$). Utilizing these factors, the primary field PVT parameters, Oil Formation Volume Factor ($B_o$), Solution Gas-Oil Ratio ($R_s$), and Gas Formation Volume Factor ($B_g$), were calculated as a function of pressure, providing the essential input required for accurate reservoir simulations and hydrocarbon initially in place (HCIIP) calculations. Furthermore, an alternative calculation methodology was applied, converting the conventional laboratory differential parameters ($B_{od}$ and $R_{sd}$) to the field-corrected values, thereby confirming the consistency of the results and ensuring reliable data for production forecasting.

---

Feel free to explore the individual project repositories for more in-depth details, code, and demonstrations. I am always eager to learn and contribute to impactful projects! 

## Let's connect! 🤝
<a href="https://www.linkedin.com/in/franklinobika" target="_blank">
  <img src="https://cdn-icons-png.flaticon.com/512/174/174857.png" alt="LinkedIn" width="40" height="40">
</a>

