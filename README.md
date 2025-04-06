# Data-Analysis-2

 Time-Series Diagnostics (Python 1)
Objective: Model volatility in temperature and humidity using GARCH and assess autocorrelation.

Key Visualizations & Methods:
ACF/PACF Plots:
Identified strong autocorrelation at lag 1 for both variables, suggesting AR(1) structure.

Correlation Heatmap:
Confirmed weak negative correlation (-0.30) between temperature and humidity.

GARCH Model Output:
Significant beta[1] values (0.98 for both variables) indicated persistent volatility clustering.
Insignificant mean model (mu), implying no drift in returns.

Findings:
Temperature volatility decreased over time; humidity volatility increased.
No significant mean drift, but strong volatility persistence.


Multivariate GARCH Analysis (Python 2)
Objective: Analyze weather data (temperature, humidity, wind speed, pressure) from Delhi (2013-2017) using statistical and time-series methods.

Key Visualizations & Methods:
Histograms:
Displayed distributions of temperature and humidity.
Revealed central clustering (e.g., most temperature observations in 15.6–20.2 range).

Line Charts:
Tracked trends over time (e.g., declining humidity with higher volatility vs. stable temperature).

Scatter Plots:
Showed negative correlation (R²=0.67) between variables (e.g., temperature vs. humidity).
Regression line: y = -2.47x + 109.36.

Box Plots (implied):
Identified outliers and data ranges.

Findings:
Weak negative correlation (-0.30) between temperature and humidity.
Humidity exhibited higher volatility over time compared to temperature.
