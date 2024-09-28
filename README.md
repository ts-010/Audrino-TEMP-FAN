# Audrino-TEMP-FAN
DIY project, that uses a temperature-controlled fan system that can adjust its speed based on the ambient temperature

# Components Required
Arduino UNO – The microcontroller to manage the system.
USB A to B Cable – For programming and powering the Arduino.
Breadboard – To build and prototype the circuit.
DHT11 Temperature & Humidity Sensor – To measure temperature.
DC Fan – The fan whose speed will vary with temperature.
2N2222 Transistor – Used to regulate fan speed based on input signals.
16x2 LCD Display – To display the temperature and fan speed.
Connecting Wires – For making connections on the breadboard.
Circuit Diagram
(Insert Circuit Diagram Here)
The circuit uses an Arduino UNO to process data from the DHT11 sensor and control the speed of the fan based on temperature readings. The 16x2 LCD display shows the real-time temperature and fan speed.

# How It Works
The DHT11 sensor continuously measures the room's temperature and humidity.
The Arduino UNO reads these values and determines the fan's speed based on pre-set temperature thresholds.
The 2N2222 transistor acts as a switch to control the fan's speed by varying the current.
The 16x2 LCD display shows the current temperature and the speed at which the fan is operating.
As the temperature increases, the fan’s speed increases, and when the temperature decreases, the fan slows down or stops.
