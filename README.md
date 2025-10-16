
# PolluCast: Live Air Pollution Predictor with Health Alerts 🌿

**PolluCast** is an IoT-based real-time air pollution monitoring and prediction system that integrates sensor data, weather APIs, and machine learning to forecast AQI levels and send health alerts.

## 🚀 Features
- Real-time data from MQ135 and DHT22 sensors via NodeMCU (ESP8266)
- Cloud storage using Thinger.io
- Integration with OpenWeatherMap and AQICN APIs
- AQI prediction using Random Forest Regressor
- Automatic health alerts via IFTTT/email

## 🧩 Tech Stack
- NodeMCU (ESP8266)
- Python
- Thinger.io
- Machine Learning (Random Forest)
- OpenWeatherMap API, AQICN API
- IFTTT Automation

## 📊 Output
- Real-time AQI values stored and visualized
- Alerts triggered when AQI > threshold levels

##ARCHITECTURAL DIAGRAM
   
Sensor/API -> Data Source  
   
CSV Storage ->Data Logging  
   
Monitoring Script -> Data Checker  
   
Alert Module -> Notification System  
   
Logging -> AQI Alert Log  
