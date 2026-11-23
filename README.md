### Crop Yield Prediction Under Climate Shocks

### From Prediction to Reality: Understanding Climate Shocks and Crop Yield in India Using Machine Learning

##  Project Overview

This project explores the application of Machine Learning to predict agricultural crop yields and understand the impact of extreme climatic conditions on agricultural productivity in India.

Using historical agricultural, climate and soil data, the project develops predictive models and simulates climate shock scenarios to analyse crop-specific vulnerability to changing environmental conditions.

##  Objectives

- Analyse historical agricultural and climatic data.
- Identify key factors influencing crop yield.
- Develop and compare machine learning regression models.
- Predict yields for selected crops.
- Simulate climate shocks and evaluate their potential impact on crop productivity.

##  Dataset

- **Records:** 19,689
- **Geographical Coverage:** 30 Indian states
- **Time Period:** 1997–2020
- **Crops Analysed:** Jute, Sugarcane, Garlic, Arecanut and Wheat.

**Key Features:** Rainfall, temperature, humidity, soil nutrients (N, P, K), pH, area, fertilizer and pesticide usage.

**Target Variable:** Crop Yield.

## Technologies Used

- Python
- Pandas & NumPy
- Matplotlib & Seaborn
- Scikit-learn
- ARIMA (Time-Series Analysis)
- Jupyter Notebook

##  Methodology

1. **Data Preprocessing:** Data cleaning, handling missing values and preparation.
2. **Exploratory Data Analysis:** Analysing distributions, outliers, correlations and crop-specific patterns.
3. **Feature Engineering:** Creating climate indicators and identifying relevant agricultural and environmental features.
4. **Model Development:** Training and comparing Linear Regression, Decision Tree, Random Forest and Gradient Boosting models.
5. **Model Evaluation:** Comparing model performance using R² and Mean Squared Error (MSE).
6. **Climate Shock Simulation:** Evaluating predicted yield changes under reduced rainfall and humidity conditions.
7. **Time-Series Analysis:** Applying ARIMA to explore annual sugarcane production trends.

## Model Performance

For the sugarcane yield prediction comparison:

| Model | Test R² |
|---|---:|
| Linear Regression | 0.509 |
| Decision Tree | 0.877 |
| Random Forest | 0.824 |
| Gradient Boosting | 0.868 |

The Decision Tree achieved the highest test R² in this comparison.

## Climate Shock Analysis

The project simulated a climate shock involving a 50% reduction in rainfall and a 15% reduction in humidity.

**Estimated crop yield reductions:**

| Crop | Yield Reduction |
|---|---:|
| Jute | 21.28% |
| Sugarcane | 18.01% |
| Garlic | 18.22% |
| Wheat | 4.56% |
| Arecanut | 1.01% |

### Key Findings

- Jute showed the highest estimated vulnerability under the simulated scenario.
- Sugarcane and Garlic also experienced considerable predicted yield reductions.
- Wheat and Arecanut demonstrated comparatively lower sensitivity.
- Tree-based models captured non-linear crop-climate relationships more effectively than the linear baseline in the sugarcane comparison.

*Note: Climate shock results are model-based scenario estimates, not observed real-world yield losses.*

## 📂 Project Presentation

Explore the complete project presentation for the analysis, visualisations, model comparisons and findings.

- [View PowerPoint Presentation](presentation/OUR%20FINAL%20PPT.pptx)
- [View PDF Presentation](presentation/Project_Presentation.pdf)

## 🚀 Future Scope

- Integrate real-time weather and climate data.
- Explore advanced models such as LSTM.
- Develop an interactive crop yield prediction dashboard.
- Improve climate risk assessment through regional data integration.

## 👩‍💻 Author

**Anamika Hari**

Data Science Graduate | Professional Fellowship in Data Science and Agentic AI Engineering

[GitHub Profile](https://github.com/anamikaghari1234)
