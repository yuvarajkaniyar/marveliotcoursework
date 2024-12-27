# Level 1 Tasks

## Task 1: Simon Says Game
This task involved creating a Simon Says game using ESP32, pushbuttons, and LEDs. The LEDs blinked in random patterns, and I had to replicate the sequence by pressing the correct buttons. If the sequence was wrong, the game restarted automatically. This helped me practice coding with ESP32 and understand random sequence generation.

![Simon Says Game Setup](#)

---

## Task 2: Basics of MQTT Protocol and Communication Protocols
In this task, I explored the MQTT protocol, focusing on its Publish/Subscribe operations, and learned about other communication and networking protocols. This gave me a solid understanding of how IoT devices communicate.

---

## Task 3: Basics of Creating a Website
I created a simple webpage with a button that toggled the background color when clicked. This task helped me get familiar with basic front-end and back-end concepts.

![Website Example](#)

---

## Task 4: ESP32 CAM-Based Surveillance Robot
This task involved building a surveillance robot using ESP32-CAM. I set up live video streaming, controlled the robot via Wi-Fi, and used the L298N motor driver for movement. It was a practical way to learn about real-time robotics and video streaming.

![Surveillance Robot Setup](#)

---

## Task 5: MQTT Publish and Subscribe
In this task, I controlled three LEDs using MQTT. By publishing messages like `LED 1 ON` or `LED 2 OFF`, I toggled specific LEDs remotely. It demonstrated the practical use of MQTT in controlling multiple devices.

![MQTT LED Control](#)

---

## Task 6: Sending Data to ThingSpeak
I used an ESP32 to send temperature data to ThingSpeak. The platform displayed the data as a temperature vs. time graph. Later, I retrieved the data for analysis, which was a great introduction to IoT data handling.

![ThingSpeak Data Plot](#)

---

## Task 7: Communication using I2C Protocol
This task involved using the I2C protocol to send data between ESP32 and Arduino. I displayed messages typed on a webserver to an LCD screen connected to the Arduino. It was an excellent hands-on experience with wired communication protocols.

![I2C Communication Setup](#)

---

## Task 9: Soil Moisture Sensor
I measured the soil moisture level using a capacitive soil moisture sensor and displayed the readings on the serial monitor. The system alerted me if the moisture level was below a threshold, which showed me how IoT can be applied in agriculture.

![Soil Moisture Sensor Setup](#)

---

## Task 10: Read and Display Vitals
I worked on measuring heart rate and oxygen levels using the MAX30100 sensor. The data was displayed on an Android app connected via MQTT or a webserver. Alerts were sent if the vitals were outside the normal range.

![Vitals Monitoring Setup](#)

---

## Task 11: Fire Alarm System with Email Alerts
This task involved building a fire alarm system using ESP32 and fire sensors. Upon detecting fire, the ESP32 sent an email alert. The task was tested in an open area under supervision for safety.

![Fire Alarm System Setup](#)

---

# Level 2 Tasks

## Task 1: Automatic Plant Watering
For this task, I designed an automated plant watering system using a solenoid valve, soil moisture sensor, and relay. The system watered the plant when moisture fell below a certain level. It was a practical way to learn about IoT applications in agriculture.

![Plant Watering System](#)

---

## Task 2: Introduction to RFID
I interfaced an RFID reader with ESP32 to read the hex code of a metro card and displayed it on an LCD. This task introduced me to RFID technology and its applications.

![RFID Reader Setup](#)

---

## Task 3: Interfacing RTC Time Module
In this task, I interfaced a DS3231 RTC module with ESP32 and displayed the real-time data on the serial monitor. It was a simple yet useful exercise in timekeeping.

![RTC Module Setup](#)

---

## Task 4: Attendance Logger
I created an attendance logger using RFID cards. The system recorded attendance with timestamps and sent the data to Google Sheets via IFTTT. It demonstrated the integration of IoT with productivity tools.

![Attendance Logger Setup](#)

---

## Task 5: Zigbee Communication
This task aimed to establish communication between Arduino and ESP32 using the Zigbee protocol to transfer sensor data. Unfortunately, I couldn’t complete it as the setup didn’t work.

![Zigbee Communication Setup](#)

---

## Task 6: Controlling Multiple Peripherals Using SPI
I used SPI communication to control a DC motor with input from an RFID module. This task helped me understand how to manage multiple peripherals using SPI.

![SPI Protocol Setup](#)

---

## Task 7: Telegram Bot Motor Control
This task involved creating a Telegram bot to control motor direction. Using ESP32, I successfully turned the motor in both directions by sending commands from the bot.

![Telegram Bot Setup](#)

---

## Task 8: Alexa Light Control
I used ESP32 to integrate an LED bulb with Alexa. By sending voice commands, I could turn the bulb on and off. This task showcased the potential of smart home integrations.

![Alexa Light Control Setup](#)
