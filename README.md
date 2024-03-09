# Urban Mobility Insights: Forecasting Bike Rentals

## INFORMATION:

Rental bikes have revolutionized transportation in many urban cities by providing greater mobility and convenience to commuters. The availability of rental bikes reduces waiting time and has become a convenient mode of transportation for residents and visitors. Accurately forecasting bike counts is crucial, but it's equally important to consider the entire supply chain that supports the biking system, from the manufacturing and distribution of bikes to the maintenance of the infrastructure. Taking a holistic approach to supply chain management ensures the biking system operates smoothly and efficiently, providing a reliable and enjoyable transportation option for all.

To achieve a sustainable and reliable rental bike system in urban areas, analyzing datasets and building predictive models is crucial. This enables city planners and bike-sharing service providers to anticipate demand fluctuations and adjust their operations accordingly. Ultimately, this contributes to the success of a rental bike system in urban areas.

## APPLICATION:

Data-driven decision making can be greatly informed by analyzing the datasets that reveal valuable insights into how weather conditions, time of day, and other factors impact bike rental patterns. These insights can be used to optimize operations not only for bike-sharing services but also for ride-sharing companies like Uber and regional players like Rapido in India, where urban mobility is a growing concern.

## DATA DISCRIPTION:
The dataset available at http://archive.ics.uci.edu/dataset/560/seoul+bike+sharing+demand contains weather information such as temperature, humidity, windspeed, visibility, dew point, solar radiation, snowfall, rainfall, along with the date and hourly bike rental information.

## Conclusion

After conducting exploratory data analysis, we identified several key variables that significantly impact the number of bikes rented on a specific day. These variables include:

- **Hour:** Rental patterns vary throughout the day, with peak demand during specific hours.
- **Temperature(°C):** Warmer days lead to higher bike rentals, while colder days see fewer rentals.
- **Humidity(%):** Lower humidity levels are associated with increased bike rentals.
- **Wind Speed (m/s):** Lower wind speeds may encourage more bike rentals.
- **Visibility (10m):** Clear and good visibility conditions attract more riders.
- **Solar Radiation (MJ/m2):** Higher solar radiation levels (sunnier days) correlate with increased rentals.
- **Rainfall(mm):** Rainy days result in fewer bike rentals.
- **Snowfall (cm):** Snowy conditions significantly reduce bike rentals.
- **Day, Month, Year:** Specific dates and seasonal variations impact rental trends.

Here is a summary of the model performance:

| Model                   | R^2     | RMSE    |
|-------------------------|---------|---------|
| Linear Regression       | 0.559   | 0.179   |
| Decision Tree Regressor | 0.761   | 0.132   |
| Random Forest Regressor | 0.869   | 0.097   |

**Random Forest Regressor** emerged as the best-performing model in our analysis.

## 

