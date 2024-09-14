The Smart Irrigation System is an IoT-based project that utilizes NodeMCU ESP8266, DHT11 temperature and humidity sensor, soil moisture sensor, water pump, and relay module to automatically water plants in a garden or farm.
The system works by measuring the temperature, humidity, and moisture level of the soil and then determining whether to water the plants or not. The NodeMCU ESP8266 is used as the main controller, which reads the sensor values, sends them to ThingSpeak cloud, and controls the water pump via a relay module.
1. The NodeMCU ESP8266 is connected to the internet via Wi-Fi and reads the temperature and humidity using the DHT11 sensor.
2. The soil moisture sensor module is used to measure the moisture content in the soil. When the moisture level is below a certain threshold value, the system activates the water pump via the relay module.
3. The moisture content in the soil is continuously monitored, and the water pump is turned off when the moisture level reaches a certain value.
4. The sensor data is sent to ThingSpeak cloud via an HTTP POST request. The data is then stored and can be analyzed to improve the watering schedule.
5. The system continues to monitor the temperature, humidity, and moisture level in the soil and automatically waters the plants when required.
