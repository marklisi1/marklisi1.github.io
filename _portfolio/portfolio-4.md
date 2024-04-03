---
title: "Projecting Agricultural Shifts using Gaussian Processes and K-Means Clustering"
excerpt: "Stochastic mathematical model to predict the viability of crops based on soil conditions. Time series data, mathematical modeling, soil analysis"
collection: portfolio
---

My goal with this project was to better understand how our shifting climate might affect one of society's most foundational industries: agriculture. Using remote sensing data from the World Soil Information Service (WoSIS) in conjunction with other public-access datasets, I implemented a stochastic mathematical model called a Gaussian process, employing Cholesky decomposition for efficient computation. It's capable of predicting values of nitrogen, phosphorus, and potassium in soil over decades-long timescales. The WoSIS data was quite messy, and any fellow data science folks reading this know that combining multiple datasets always requires some tinkering. 

[You can read the paper and check out the associated code here!](https://github.com/marklisi1/agricultural-shifts/blob/main/Agricultural-Shift-Prediction.pdf)

* Skills: Mathematical modeling, time series data, EDA/ETL, data processing/visualization
* Tools: scikit-learn, Pandas, NumPy
