# SimpleTemperatureHumidityStation
Portable temperature and humidity station using basic electronic components.

# Components used: 
Arduino NANO, DHT-11 Temperature and Humidity Sensor, LCD with I2C module, 9V battery, external power supply module, Jumper wires and Single-strand wires.

# Software: 
Arduino IDE

I have included pictures and a video of the setup. Do check it out.

# Basic Logic and Working: 
Read temperature in both degree celsius and fahrenheit from the DHT-11 temperature and humidity sensor. Display readings for 5 seconds and clear the display. Delay for 1 second, take the readings again. This process repeats.
The board, display, sensor are all powered by the 9V battery with an external power supply which caps-off the voltage to 5V. This makes the station portable. 







