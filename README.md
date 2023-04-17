# smartweatherstation 
we have created a proper Weather Monitoring System using NodeMCU with
WiFi Module ESP8266 -12E, Temperature and humidity sensor DHT11,
Atmospheric pressure sensor BMP180, Digital Light Sensor BH1750FVI, Mini
Breadboards, OLED Display, Jumper wires, USB Cable. It was able to correctly
detect the values of the weather conditions present around, like – Temperature
(deg. Celcius), Atmospheric Pressure (pascals), Light Intensity (Lux (lx)) and
Humidity (%).
The detected parameter values were updated to a channel server created on
thingspeak (a matlab tool) to visualize the graphs of the collected data. A local
Web Page was created for the simulation view of the results, which fetched the
data back from thingspeak server API.
pdf doc for the same has been attached for reference
