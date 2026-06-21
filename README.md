Smart Gas & Flame Alert System

Overview-

A smart safety monitoring system developed using Arduino Uno, MQ-2 Gas Sensor, Flame Sensor, SSD1306 OLED Display, Relay, Buzzer, and LEDs.
The system continuously monitors gas leakage and flame detection. When an emergency condition occurs, it activates an alarm and cooling fan while displaying the status on an OLED screen.

Features-

* Gas leakage detection
* Flame detection
* OLED display monitoring
* Gas alert LED
* Flame alert LED
* Buzzer alarm
* Automatic fan control
* Real-time status display
* Proteus simulation

![Normal Condition](normal%20condition.png)

Components Used-

* Arduino Uno R3
* MQ-2 Gas Sensor (simulated using potentiometer)
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

Working Principle---

1. The gas sensor continuously monitors gas concentration.
2. The flame sensor detects fire/flame conditions.
3. OLED displays:
    * Gas Value
    * Gas Status (SAFE/ALERT)
    * Flame Status (DETECTED/NOT DETECTED)
    * Fan Status
4. Gas and flame alerts activate LEDs.
5. Buzzer and fan are activated during emergency conditions.

Software Used--

* Arduino IDE
* Proteus 8 Professional

  
Future Enhancements

* ESP32 Wi-Fi Integration
* Telegram Alert System
* Web Dashboard
* ThingSpeak Cloud Monitoring
* Mobile Application

_________________________________________________________________
Author
Pritam Kumar
Electrical & Electronics Engineering (EEE)
Lok Nayak Jai Prakash Institute of Technology (LNJPIT), Chapra
