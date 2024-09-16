Overview
This project demonstrates how to interface a DHT11 (or DHT22) temperature and humidity sensor with an ESP8266 microcontroller. The code reads temperature and humidity data from the DHT sensor and prints the values to the Serial Monitor. This example is useful for understanding basic sensor interfacing and serial communication with the ESP8266.

Components
ESP8266 Board (e.g., NodeMCU, Wemos D1 Mini)
DHT11 or DHT22 Sensor
Breadboard and Jumper Wires
Wiring

Connect the DHT sensor to the ESP8266 as follows:
DHT11/DHT22 VCC to ESP8266 3.3V
DHT11/DHT22 GND to ESP8266 GND
DHT11/DHT22 DATA to ESP8266 D4 (GPIO2)

![iotwkshp TINKER CAD](https://github.com/user-attachments/assets/20d3f1bb-1429-4932-b94e-9e52aa8d26aa)


Installation
Clone the repository:
Copy code
git clone :https://github.com/abhijit826/ESP8266-Wi-Fi-microcontroller-Temperature-and-Humidity-Measurement
Install necessary libraries:

Adafruit Sensor Library
DHT Sensor Library
You can install these libraries via the Arduino Library Manager or download them from the Adafruit GitHub repository and DHT Sensor GitHub repository.
Upload the code to your ESP8266 board using the Arduino IDE.
Open the Serial Monitor (set to 115200 baud) to view the temperature and humidity readings
