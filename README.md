# Data Science Portfolio
This repository contains my personal data related works that includes state-of-art data science, data cleaning, data manipulation, machine learning, statistical tests, as well as financial analysis and crypto bot projects. These works are completed for academic studies, real-life projects and hobby interests.
The tools utilized for these projects are mostly jupyter lab, but also includes further tools, e.g., Tableau. 

### Tools
  - **Python**: NumPy, Pandas, Seaborn, Matplotlib, Plotly
  - **Machine Learning**: Scikit-learn, Scipy, Statsmodels
  - **Data Visualization**: Tableau
  - **Crypto Trading**: gate_api, binance
  - **Financial Analysis**: Mplfinance

### Contents
- ## End-to-End Data Science Projects

    - [Vehicle Insurance Charge Prediction](https://github.com/DrFarukAydin/data-science-portfolio/blob/main/end-to-end-projects/vehicle_insurance_prediction.ipynb): Die Aufgabe besteht in der Modellierung der zu erwartenden Schadenhöhe pro Versicherungsnehmer und Jahr anhand der Risikomerkmale der Kunden. GLM Regressors zb. TweedieRegressor, GammaRegressor und state-of-art Algorithmen wie GradientBoosting, XGB und LGBM sind ausprobiert. Nahezu perfekte Ergebnisse werden mit GradientBoosting-Algorithmen erzielt.
    
    - [Fraud Detection in Insurance Claims](https://github.com/DrFarukAydin/data-science-portfolio/blob/main/end-to-end-projects/insurance_fraud.ipynb): In this work, frauds from insurance claims are detected using scikit-learn ML classification algorithms and anomality detection techniques such as oversampling with SMOTE. 86% of the frauds are catched and decisive factors are determined. Additionally, an [interactive Tableau dashboard](https://public.tableau.com/app/profile/omer.faruk.aydin/viz/InsuranceFraudsDashboard/Dashboard1?publish=yes) is created.

    - [Customer Segmentation for Life Insurance](https://github.com/DrFarukAydin/data-science-portfolio/blob/main/end-to-end-projects/insurance_customer_segmentation.ipynb): In this work, severity of customer claims are predicted using sci-kit learn classification algorithms. 8 class of customer responses are classified. Pairwise classification is applied to increase accuracy score and 84% accuracy is achieved. 
    
    - [Prediction of Insurance Charges](https://github.com/DrFarukAydin/data-science-portfolio/blob/main/end-to-end-projects/insurance_predict_charges.ipynb): In this work, the dataset can be used to predict insurance charges using ML regression algorithms based on the age, sex, and BMI of a customer. 81% R2 score is achieved. Finally, a pipeline is created to automate the preprocessing and modelling steps for the end users.
    
    - [Life Expectancy Analysis](https://github.com/DrFarukAydin/data-science-portfolio/blob/main/end-to-end-projects/insurance_life_expectancy.ipynb): The factors affecting life expectancy is analysed. Regression algorithms are implemented to predict life expectancy and a pipeline is created to automate the processes. 93.9% R2 score is achieved.



- ### Data Collection, Merging and Data Cleaning (Jupyter-Python)
    - [Mobility Change during COVID19](https://github.com/DrFarukAydin/data-science-portfolio/blob/main/data-collection-merging-and-cleaning/mobility-dataframe-preparation.ipynb): In this work, Google Mobility Data, GDP per capita, weather data, COVID19 case records, city development index, traffic congestion index, fuel prices are collected, all dataframes are cleaned and merged in a single dataframe. 
    - [Data Cleaning with Human-Intelligence](https://github.com/DrFarukAydin/data-science-portfolio/blob/main/data-collection-merging-and-cleaning/data-cleaning-for-hr-classification.ipynb): This work contains various data cleaning methods, as well as data imputation with ML algorithms. The importance of manual data cleaning and filling missing values for saving valuable data and maintaining bias of data is explained with a real-world case study.
    - [Data Visualization for Financial Analysis](https://github.com/DrFarukAydin/data-science-portfolio/blob/main/financial-tools/data-visualization-finance.ipynb): Candlesticks visualization with MPLFinance with Supertrend and MOST indicators, as well as RSI.

- ### Data Visualization (Jupyter-Python)
    - [COVID19 vs Mobility Data Visualization](https://github.com/DrFarukAydin/data-science-portfolio/blob/main/data-visualization-python-jupyter/mobility-data-analysis-visualization.ipynb): Mobility during COVID19 pandemic is visualized in Jupyter-Notebook to get better first insight of the data. In this work mobility change is analyzed considering locations, well-being, number of cases and similar records, weather, traffic and so on.
    
- ### Data Visualization (Tableau)
    - [COVID19 Mobility Evaluation](https://github.com/DrFarukAydin/data-science-portfolio/blob/main/data-visualization-tableau/data-visualization-tableau.ipynb): Mobility during COVID19 pandemic is visualized with Tableau to get better first insight of the data. In this work mobility change is analyzed considering locations, well-being, number of cases and similar records, weather, traffic and so on.
    
- ### Machine Learning (Jupyter-Python)
    - [Regression Analysis: Wind Turbine Energy Output Prediction ](https://github.com/DrFarukAydin/data-science-portfolio/blob/main/machine-learning/regression-wind-turbine.ipynb): To predict energy output, various imputation (LGBM Imputer, KNNImputer, etc.) and train-test split (StratifiedKFold) methods applied with various Regressors (ElasticNet, KNN Regressor, SVM, MLP Regressor (Neural Network), Decision Tree, Bagging, RandomForest, ADABoost, GradientBoosting, XGBoost, LGBM and CatBoost Regressors). 
    - [Classification for Human Resources](https://github.com/DrFarukAydin/data-science-portfolio/blob/main/machine-learning/classification-hr.ipynb): In this work, some state-of-art classification algorithms are performed to decide which candidates looking for a job change. Logistic Regression, Gaussian Naive Bayes, KNeighbors, SVC, Neural Network (MLP), DecisionTreeClassifier, Random Forests, GradientBoosting, XGBoost, LightGBM, CatBoost and Perceptron algorithms are created and tuned using RandomizedSearchCV. The results are compared to find the best algorithm for this particular dataset. Furthermore, the most effective features for the target value are evaluated. 
    - [Clustering Countries by COVID19 Mobility Behaviour](https://github.com/DrFarukAydin/data-science-portfolio/blob/main/machine-learning/mobility-cluster.ipynb): The countries are clustered with KMeans and DBScan by their mobility behaviour to draw meaningful insights.
    - [Natural Language Process (NLP)](https://github.com/DrFarukAydin/data-science-portfolio/blob/main/machine-learning/NLP.ipynb): Some job ads and a resume are processed with NLP techniques to score similarities. 
     
- ### Statistical Analysis (Jupyter-Python)
    - [Statistical Analysis of COVID19 Mobility](https://github.com/DrFarukAydin/data-science-portfolio/blob/main/statistical-analysis/mobility-statistical-tests.ipynb): The relationships between weather, city and county development index and mobility behaviour are analyzed using Shapiro, Levene, Mann-Whitney U, Kruskal Wallis H and Dunn tests. 
    - [Effect of Fuel Prices on Mobility Behavior](https://github.com/DrFarukAydin/data-science-portfolio/blob/main/statistical-analysis/fuel-mobility-relationship.ipynb): The relationship between fuel prices and mobility behaviour are analyzed for religional holidays time range by data visualization and using Shapiro, Levene, Mann-Whitney U tests.  
    
- ### Financial Analysis, Technical Indicators (Jupyter-Python)
    - [Crypto Trading Bot for Binance](https://github.com/DrFarukAydin/data-science-portfolio/blob/main/financial-tools/binance-bot.ipynb): Creating a trader bot that can automatically buy/sell crypto on Binance.
    - [Crypto Trading Bot for Gate.io](https://github.com/DrFarukAydin/data-science-portfolio/blob/main/financial-tools/gate-io-bot.ipynb): Creating a trader bot that can automatically buy/sell crypto on Gate.io.
    - [Technical Indicators for Financial Analysis](https://github.com/DrFarukAydin/data-science-portfolio/blob/main/financial-tools/technical-indicators-finance.ipynb): Functions for technical indicators, i.e., SuperTrend, MOST (Moving Stop Loss), RSI. 
    
**Contact:**
- [LinkedIn](https://www.linkedin.com/in/faruk-aydin-0350a459/?locale=en_US)
- Mail: farukaydin21@gmail.com
- Published Works: [Google Scholar](https://scholar.google.com/citations?user=JTdaPdYAAAAJ&hl=tr&oi=ao)


  

