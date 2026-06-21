<div align="center">
<h1><b><i>🚀 Smart Gas & Flame Alert System</b></i></h1></div>



Overview-

A smart safety monitoring system developed using Arduino Uno, MQ-2 Gas Sensor, Flame Sensor, SSD1306 OLED Display, Relay, Buzzer, and LEDs.
The system continuously monitors gas leakage and flame detection. When an emergency condition occurs, it activates an alarm and cooling fan while displaying the status on an OLED screen.
<hr>
✨ Features

* 🔥 Gas Leakage Detection
* 🚨 Flame Detection
* 📟 OLED Display Monitoring
* 💡 Gas Alert LED
* 💡 Flame Alert LED
* 🔔 Buzzer Alarm
* 🌪️ Automatic Fan Control
* 📊 Real-Time Status Display
* 🖥️ Proteus Simulation
<hr>

![Normal Condition](normal%20condition.png)

<hr><h2>🔧 Components Used</h2>

* Arduino Uno R3
* MQ-2 Gas Sensor
* Flame Sensor
* SSD1306 OLED Display (128×64 I2C)
* Relay Module
* DC Fan
* Buzzer
* LEDs
* Proteus 8 Professional

## Pin Configuration

| Component | Arduino Pin |
|-----------|------------|
| Gas Sensor | A0 |
| Flame Sensor | D2 |
| Gas LED | D6 |
| Flame LED | D7 |
| Indicator LED | D8 |
| Buzzer | D10 |
| Relay/Fan | D11 |
| OLED SDA | A4 |
| OLED SCL | A5 |

<hr>
⚙️ Working Principle

1. Gas sensor continuously monitors gas concentration.
2. Flame sensor detects fire/flame conditions.
3. OLED displays:
    * Gas Value
    * Gas Status (SAFE/ALERT)
    * Flame Status (DETECTED/NOT DETECTED)
    * Fan Status
4. LEDs indicate gas and flame alerts.
5. Buzzer and fan activate automatically during emergency conditions.
<hr>

Software Used--

* Arduino IDE
* Proteus 8 Professional

<hr>  
🚀 Future Enhancements

* ESP32 Wi-Fi Integration
* Telegram Alert System
* Web Dashboard
* ThingSpeak Cloud Monitoring
* Mobile Application
<hr>
Developed By
<div align="center">
<h1 style="color:#0A66C2;">Pritam Kumar Gupta</h1>  
</div>
<br>
Electrical & Electronics Engineering (EEE)<br>
Lok Nayak Jai Prakash Institute of Technology (LNJPIT), Chapra
