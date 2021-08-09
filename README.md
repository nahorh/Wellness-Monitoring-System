# Wellness-Monitoring-System
This system basically checks for the heart rate and the temperature of the user and displays it on the LCD.
It uses the following components:
1) LM35 sensor.
2) SEN11574 sensor.
3) 16x2 LCD display.
4) 8051 MCU.

The 8051 checks one by one the sensor values and compares it with the normal values of temperature.

There is no fixed normal heart rate value for everyone so heart rate is not compared with any value.

If the temperature exceeds 37.5ͦ  then the buzzer sounds indicating the person has temperature or fever.
