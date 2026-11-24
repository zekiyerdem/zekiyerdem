### Hi, I'm Zekiye 👋
**Data Scientist | PhD in Electrical Engineering (Photovoltaics) | Solar & Energy Analytics**

I work where energy physics meets data: PV performance, irradiance and temperature effects, and the messy plant telemetry that comes with them. I build forecasting and anomaly-detection models and check them against physical models, not just statistical fit.

**What I work on**
- ⚡ Energy demand and solar forecasting (ARIMA, LSTM, gradient boosting)
- 🔌 Smart meter analytics: load segmentation and clustering, EV charging detection
- 🔍 Data quality for sensor and SCADA time series: faults, clock drift, gap filling
- ☀️ PV modelling with pvlib: clear-sky checks, plane-of-array irradiance, performance ratio

**Featured projects**
- [ev-charging-detection](https://github.com/zekiyerdem/ev-charging-detection): finds homes that charge an electric vehicle, estimates how many, and estimates EV load by hour from hourly smart meter data alone, using engineered block-load features, a K-Means consensus vote and a charger-power check. On 630 simulated Ontario homes it finds 118 of 120 EV homes with no false alarms and captures the 11 pm overnight-rate charging peak; a stress test and GMM/HDBSCAN comparisons show where it breaks.
- [ontario-demand-forecast](https://github.com/zekiyerdem/ontario-demand-forecast): day-ahead forecasting of Ontario's hourly electricity demand from public IESO and weather data. LightGBM reaches 2.6 % MAPE on 2025, 41 % below persistence.
- [pv-data-quality](https://github.com/zekiyerdem/pv-data-quality): automated QC and degradation analysis on 13 years of 1-minute NREL PVDAQ field data. It finds a hidden one-year outage, sensor faults and timestamp offsets, and estimates −0.30 %/yr degradation, validated against RdTools.

**Background**
13 peer-reviewed publications in renewable energy and power electronics (340+ citations) · 7 years of data science consulting · Lead Instructor, Data Science at TMU

**Toolkit:** Python (pandas, NumPy, scikit-learn, TensorFlow, pvlib) · SQL · Power BI · Azure/GCP

📫 [LinkedIn](https://www.linkedin.com/in/zekiye-erdem-ca)
