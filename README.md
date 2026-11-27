# Climate-Resilient Crop Yield Prediction | Machine Learning & Climate Risk Analysis

**Predictive Analytics | Machine Learning | Agricultural Intelligence | Climate Impact Assessment**

An end-to-end machine learning project analysing the relationship between climate conditions, soil characteristics and agricultural productivity across India. Compares predictive models, identifies key yield-driving factors and simulates drought scenarios to assess crop vulnerability and support climate-aware agricultural planning.

## 🔗 Project Links
- **GitHub Repository:**(https://github.com/anamikaghari1234/crop-yield-prediction-under-shocks.git)


## 🎯 Business Problem

Climate variability, unpredictable rainfall and changing soil conditions create significant uncertainty in agricultural productivity. This project applies machine learning to predict crop yields, identify climate-sensitive crops and quantify potential production losses under simulated drought conditions.

## 📊 Dataset Overview

| Attribute | Details |
|---|---|
| Total Records | 19,689 |
| Geographic Coverage | 30 Indian states |
| Time Period | 1997–2020 |
| Target Variable | Crop Yield (kg/ha) |
| Crops Analysed | Sugarcane, Wheat, Jute, Garlic, Arecanut |
| Input Features | Temperature, rainfall, humidity, soil nutrients, pH and cultivated area |

## ⚙️ Data Processing & Exploratory Analysis

- **Data Preparation:** Consolidated agricultural, climate and soil-related variables into a unified analytical dataset.
- **Exploratory Data Analysis:** Examined yield distributions, correlations, regional patterns and crop-specific climate relationships.
- **Outlier Analysis:** Identified extreme observations in yield, rainfall, temperature and nitrogen while retaining genuine climate extremes for shock analysis.
- **Feature Selection:** Evaluated feature relationships and prioritised influential predictors to reduce redundancy.
- **Visual Analytics:** Used distribution analysis, correlation heatmaps and comparative plots to interpret agricultural patterns.

## 🤖 Machine Learning Models

Four regression algorithms were evaluated to identify the most effective crop-yield prediction approach.

| Algorithm | Test R² | Key Strength |
|---|---:|---|
| Linear Regression | 0.509 | Interpretable baseline |
| Decision Tree | **0.877** | Non-linear pattern detection |
| Random Forest | 0.824 | Robust predictions |
| Gradient Boosting | 0.868 | Ensemble-based prediction |

**Best Performing Model:** Decision Tree Regressor, achieving a test R² of **0.877** for Sugarcane yield prediction.

## 📈 Key Results & Business Insights

### 1. Crop Yield Prediction
- Achieved a test R² of 0.877 for Sugarcane using Decision Tree Regression.
- Recorded crop-specific test R² scores of 0.804 for Arecanut, 0.877 for Sugarcane, 0.737 for Jute, 0.750 for Garlic and 0.811 for Wheat.
- Identified soil pH, humidity, potassium and temperature as influential yield-related factors.

### 2. Climate Shock Simulation
Simulated drought conditions by reducing rainfall by 50% and humidity by 15% to estimate crop vulnerability.

| Crop | Estimated Yield Decline |
|---|---:|
| Jute | 21.28% |
| Sugarcane | 18.01% |
| Garlic | 18.22% |
| Wheat | 4.56% |
| Arecanut | 1.01% |

**Key Insight:** Jute, Sugarcane and Garlic demonstrated higher vulnerability, while Wheat and Arecanut showed comparatively greater resilience under the simulated conditions.

### 3. Sugarcane Drought Assessment
- Estimated a decline in average yield from 47.13 to 38.64 under simulated drought conditions.
- Quantified an approximately 18% yield reduction, highlighting the crop's dependence on water availability.

### 4. Time-Series Forecasting
- Applied ARIMA to annual Sugarcane production data.
- Identified limitations in capturing long-term production growth and external influencing factors.

## 🛠️ Technology Stack

- **Programming:** Python
- **Data Manipulation:** Pandas, NumPy
- **Data Visualisation:** Matplotlib, Seaborn
- **Machine Learning:** Scikit-learn
- **Time-Series Analysis:** ARIMA, Statsmodels
- **Development Environment:** Jupyter Notebook

## 💼 Business Applications

- **Agriculture:** Crop-yield forecasting and productivity assessment.
- **Government & Policy:** Climate vulnerability assessment and agricultural planning.
- **Agri-Tech:** Data-driven crop recommendations and risk monitoring.
- **Supply Chain:** Production forecasting and agricultural resource planning.

## 🚀 Future Scope

- Integrate real-time weather and soil datasets.
- Explore LSTM and hybrid forecasting architectures.
- Build climate-adaptive crop-yield prediction systems.
- Extend drought and extreme-weather simulations to additional crops.

## 👩‍💻 Project Contribution

Conducted exploratory data analysis, feature selection, regression model comparison, crop-specific performance evaluation and simulated climate-shock assessment to identify agricultural productivity patterns and climate-related yield risks.
