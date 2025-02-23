# Sunspot Prediction

The number of sunspots observed on the surface of the Sun varies from year to year. The Sun is most active during periods of sunspot maximums, emitting the highest levels of energy and radiation into Earth's environment. 

During these peak periods, the Earth experiences:
- Increased occurrences of the **Northern and Southern Lights** (Auroras).
- Possible **disruptions in radio transmissions** and **power grids**.

### **Why Sunspot Tracking is Important**
Monitoring sunspot activity helps in predicting space weather events that can impact communication systems, satellite operations, and power infrastructure. 

This project aims to analyze and forecast sunspot counts using various time series modeling techniques.

---
## **Models Implemented**
- **ARIMA**: AutoRegressive Integrated Moving Average  
- **SARIMAX**: Seasonal AutoRegressive Integrated Moving Average with Exogenous Regressors  
- **Smoothed ARIMA**: ARIMA model with preprocessing to remove noise  

### **Dataset**
The dataset contains historical sunspot counts recorded over time, used for training and evaluation of different forecasting models.

### **Usage**
Clone this repository and run the notebooks to explore sunspot forecasting:
```sh
git clone https://github.com/Kameshwaran-45/Sunspot-Prediction.git
cd Sunspot-Prediction
