# Smart Water Level and Temperature Monitoring System
## Description
The Smart Water Level and Temperature Monitoring System is an Arduino-based project that monitors water levels and temperature in a tank or reservoir. The system uses an ultrasonic sensor for measuring water levels and an analog temperature sensor to monitor temperature. Real-time data is displayed on a 16x2 LCD screen, and the motor is controlled automatically based on predefined water level and temperature thresholds.
## Features
- Measures water level using an ultrasonic sensor.
- Monitors temperature with an analog temperature sensor.
- Displays real-time water level and temperature readings on a 16x2 LCD screen.
- Automatically controls a motor based on temperature and water level conditions.
- Alerts when the motor overheats or water level is too low.
## Components
1. Arduino board
2. Ultrasonic sensor (for water level measurement)
3. Analog temperature sensor (e.g., LM35)
4. 16x2 LCD display
5. Motor
6. Connecting wires

## Circuit Connections
- LCD Pins: Connect pins 6, 7, 8, 9, 10, and 11 to the LCD screen.  
- Ultrasonic Sensor:
  - Trig pin: Connect to digital pin 4 on the Arduino.  
  - Echo pin: Connect to digital pin 3 on the Arduino.  
- Temperature Sensor:  
  - Analog output connects to pin A0 on the Arduino.  
- Motor: Connect the motor control pin to digital pin 5 on the     Arduino.

## License
This project is open-source and available under the MIT License.
