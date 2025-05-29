✅ System Overview
•	ESP32 AP mode with a local webserver (WebServer.h)
•	DHT11 for Temp & Humidity
•	BMP180 for Pressure
•	Soil moisture via analog
•	Rain sensor via analog
•	Tilt via analog and digital
•	Stepper motor control (via Stepper library)
•	Web interface to display sensor data and control motor

Sample Wiring (DHT22 example)
DHT22
VCC → 3.3V
GND → GND
Data → GPIO 4 (with 10kΩ pull-up resistor to 3.3V)
