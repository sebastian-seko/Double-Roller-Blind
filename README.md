# Double-Roller-Blind

Original code from [original code] https://github.com/RoadkillUK/Motor-on-a-Roller-Blind-for-ESPHOME

This setup uses a NodeMCUv3 and 2x (28BYJ-48 stepper motor + ULN2003 driver board)
``` 
Connection Motor 1

Driver IN1 to D0 (GPIO 16) NodeMCU
Driver IN2 to D2 (GPIO 4) NodeMCU
Driver IN3 to D1 (GPIO 5) NodeMCU
Driver IN4 to D3 (GPIO 0) NodeMCU
Driver Vin to Power Supply VCC
Driver GND to Power Supply GND

Connection Motor 2

Driver IN1 to D6 (GPIO 12) NodeMCU
Driver IN2 to D4 (GPIO 2) NodeMCU
Driver IN3 to D7 (GPIO 13) NodeMCU
Driver IN4 to D5 (GPIO 14) NodeMCU
Driver Vin to Power Supply VCC
Driver GND to Power Supply GND
```