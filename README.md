# Real Estate Price Forecasting Platform

This project presents a time series forecasting platform designed to assist real estate investors in making data-informed decisions by predicting property prices and estimating investment returns under various market conditions.

## Project Overview

Developed as a final course project for a Time Series Analysis class, this platform offers:

- Multi-horizon housing price forecasts (1Y, 2Y, 5Y, etc.)
- ROI estimation based on location, budget, and property attributes
- Investment recommendations (e.g., Buy, Hold, or Wait) based on projected trends

The platform addresses three key challenges for individual investors:
1. Difficulty in accurately forecasting real estate market trends
2. Fragmented and inconsistent data sources
3. Limited exploration of unfamiliar but high-potential regions

## Use Case

**Target Users:** Individual property investors  
**Objectives:**  
- Maximize return on investment (ROI)  
- Identify high-potential markets beyond personal familiarity  
- Respond to market changes with real-time insights  

## Methodology

### Models Used
- `AutoARIMA`: Main forecasting model optimized for seasonality and short-term price prediction
- `XGBoost`: Supplementary model incorporating macroeconomic features (GDP, interest rates, employment)

### Input Features
- Historical median home prices and rental rates
- Regional economic indicators (population growth, migration, construction permits, lending data)

## Technology Stack

- Python (pmdarima, XGBoost, pandas, matplotlib)
- Jupyter Notebook
- Git and GitHub for version control
- Deployment options: Streamlit or Flask (future work)

## Interface Preview

Refer to [wireframe.pdf](./wireframe.pdf) for visual design prototypes.  
The interface includes the following modules:

- ROI forecasting over multiple time horizons  
- Regional investment recommendations  
- Interactive location-based insights  

## Example Output
ROI Forecast (Austin, TX):
1-Year: 3.2%, 2-Year: 4.5%, 5-Year: 5.0%
Recommendation: Ideal time to buy


## How to Run

1. Clone this repository
2. Open `TS_final.ipynb` using Jupyter Notebook
3. Modify location and input parameters as needed
4. Execute cells to generate forecasts and recommendations

## Project Files

- `TS_final.ipynb`: Complete forecasting and analysis pipeline
- `presentation_slide.pdf`: Summary presentation
- `wireframe.pdf`: UI/UX design mockups




