#  IoT Smart Agriculture & Automatic Irrigation System (ESP8266)

> Automating irrigation with soil moisture & environmental monitoring powered by IoT and NodeMCU ESP8266.

<p align="center">
   <img width="906" height="504" alt="image" src="https://github.com/user-attachments/assets/f1317ef8-c35d-40b5-a74a-1b52329d8567" />
</p>

---

##  Overview
Agriculture is the backbone of many economies, but **traditional farming methods** often result in inefficient water usage and reduced crop productivity.  
This project aims to solve these issues with an **IoT-enabled Smart Agriculture & Automatic Irrigation System**.  

It uses the **NodeMCU ESP8266** microcontroller to:
- Monitor **soil moisture**, **air temperature**, and **humidity**.
- Automatically control water irrigation using a **relay-controlled pump**.
- Provide **remote monitoring** through the **ThingSpeak IoT platform**.

This system ensures **optimized water usage, reduced manual intervention, and improved crop yield**.

---

##  Features
-  **Automated Irrigation** – turns the water pump ON/OFF based on soil moisture.
-  **Environment Monitoring** – tracks air temperature & humidity.
-  **IoT Connectivity** – view live sensor data anywhere via ThingSpeak.
-  **Water Conservation** – prevents over-irrigation and reduces waste.
-  **Low-Cost & DIY Friendly** – built using readily available components.

---

##  Bill of Materials
| S.No | Component                              | Quantity |
|------|----------------------------------------|----------|
| 1    | NodeMCU ESP8266 Board                  | 1        |
| 2    | Capacitive Soil Moisture Sensor        | 1        |
| 3    | 0.96" I2C OLED Display                 | 1        |
| 4    | DHT11 Humidity & Temperature Sensor    | 1        |
| 5    | 1-Channel 5V Relay Module              | 1        |
| 6    | 5V DC Submersible Pump                 | 1        |
| 7    | Connecting Wires                       | 10       |
| 8    | Breadboard                             | 1        |

---

##  System Architecture

<p align="center">
   <<img width="737" height="537" alt="image" src="https://github.com/user-attachments/assets/1b8246ee-60dc-4e42-aed6-06f7f592adf7" />>
</p>


## Install required libraries:
   step - 1 
- [Adafruit GFX](https://github.com/adafruit/Adafruit-GFX-Library)  
- [Adafruit SSD1306](https://github.com/adafruit/Adafruit_SSD1306)  
- [DHT Sensor Library](https://github.com/adafruit/DHT-sensor-library)  

  step - 2: Connect NodeMCU to your PC via USB.  
  step - 3: Open the provided `.ino` sketch in Arduino IDE.  
  step - 4: Update your Wi-Fi credentials & API Key.  
  step - 5: Upload the code to NodeMCU.  
  step - 6: Power up the circuit & start monitoring on **ThingSpeak**.  

---

##  PCB Option
For a more compact solution, you can design a **PCB** using EasyEDA.  
- Gerber files are available in `/PCB` folder.  
- Order your PCB from services like [ALLPCB](https://www.allpcb.com/) or JLCPCB.  

 *(Insert PCB front & back image here)*

---

##  Applications
-  Smart precision agriculture.  
-  Home garden automation.  
-  Greenhouse monitoring.  
-  Agricultural research and academic projects.  

---

##  Future Improvements
-  Mobile app notifications for irrigation status.  
-  Switch to **Blynk/Firebase** for a more interactive dashboard.  
-  Add **solar panel power supply** for sustainability.  
-  Integrate **rain sensors** for weather-based irrigation.  
-  Use **LoRaWAN** for long-distance data transmission.  
  


