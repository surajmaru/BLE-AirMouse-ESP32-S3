# 🖱️ BLE Air Mouse ESP32 S3 
**In this project i have shown how to make a complete wireless mouse using an ESP32 S3 with some other components like ESP32 S3, MPU6050, TP4056 charger, MT3608 boost converter, li-ion 18650 battery, 2 push buttons, few wires and heavy soldering skills :)**

# ⚡Schematics

<img width="1906" height="878" alt="Screenshot 2025-11-27 181440" src="https://github.com/user-attachments/assets/fb9f5e1d-ba23-41ec-9c4f-6343197fb839" />


# 🔥 Features
**This BLE mouse works just like a regular mouse but has some more advantages like:**
- Its completely wireless and works on a big battery.
- Comfortable to hold in hand for a long period of time.
- Super easy to use and handle.
- One single charge and it works for days.
- Has left click, Right click, scroll up and down and gyroscope gestures and can be modified at any time.

# 🫡 Connections

| Battery (1S Li-ion) 3.7V| Boost Converter 5V |
|--------------------|-------------------------|
|    +               |  +                      |
|    -               |  -                      |


| Boost Converter 5V | ESP32 S3 Pin |
|---------------------|-------------|
|    +                |  VCC        |
|    GND              |  GND        |
 

| ESP32 S3 Pin | MPU6050 |
|--------------|---------|
| 5V(VCC)      |  VCC    |
| GND          |  GND    |
| 10           |  SCL    |
| 11           |  SDA    |


| ESP32 S3 Pin | Button |
|--------------|--------|
| GND          |  GND   |
| 4            |  BTN 1 |
| 5            |  BTN 2 |

# The code is given above 👆.

# Watch my Youtube video:- 
