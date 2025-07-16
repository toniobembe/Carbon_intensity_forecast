# 📈 Forecasting UK Carbon Intensity Using Weather, Time & Lag Features
Not all electricity is created equally when it comes to environmental impact. How green the UK's electricity grid is varies depending on how that electricity is generated, whether wind, solar, gas or nuclear, and this mix can vary dramatically in a day. 
In this project I set out to explore whether I could predict those fluctuations, using features like weather, time of day and recent trends.

[Read the full blog post on Medium](https://medium.com/@oluwatoni.obembe/forecasting-uk-carbon-intensity-using-weather-time-and-lag-features-44369d889e29)

##Project Structure
- `data/` – Cleaned and raw datasets
- `notebooks/` – Jupyter notebook for data exploration and modelling(1.pulling 2.exploring 3.modelling)
- `models/` – Trained model files 
- `visuals/` – Plots and SHAP explanations

##Tools and technologies
- Python(Pandas, seaborn, XGBoost, SHAP)
- Open-Meteo API
- National Grid Carbon Intensity API
- Matplotlib and Seaborn

##Key features
- Merged carbon intensity with weather and calendar data
- XGB for predictive modelling
- Explored explainabiity using SHAP
- Compared with intensity forecasts
