**Detailed Description: Real-Time Data Processing System for Weather Monitoring**
**Objective**
The goal is to create a real-time system that monitors weather conditions and delivers summary insights, such as daily rollups and aggregates, using data from the OpenWeatherMap API.
**Data Sources**
It will continuously retrieve meteorological data for India's major cities, including Delhi, Mumbai, Chennai, Bangalore, Kolkata, and Hyderabad.
**Processing and Analysis**
The system will call the API at regular intervals (for example, every 5 minutes) to retrieve weather data for the given cities. Process tasks include:
**Data retrieval:**
-Continuously retrieve real-time data via API requests.
-Parse and save data for each city.
**Temperature Conversion:**
-Convert Kelvin temps to Celsius for better readability.
**Rollups and aggregates.**
This section focuses on summarizing weather data throughout time:
**Daily weather summary**: 
-Roll up data for each day. 
-Collect data points for 24 hours and provide daily insights.
**Daily aggregates:**
-Average temperature is calculated as the average of all temperatures collected throughout the day.
-Maximum temperature: The maximum temperature observed during the day.
-Minimum temperature: The lowest temperature observed during the day.
-The dominant weather condition is the most common (for example, "Clouds" if it was predominantly cloudy).
**Visualizations**
-Create visual insights for users.
-everyday weather summaries are graphical representations of everyday temperatures and conditions.
**Historical Trends**: Show temperature trends (max, min, and average) over days, weeks, or months.
**Triggered Alerts**: Show instances where thresholds were exceeded.
**Suggested Visualization Libraries:**
-Matplotlib is a tool for plotting trends.
-Seaborn: For improved heatmaps and condition trends.
Test cases should be developed to validate the behavior of the system in order to guarantee its resilience. 


