# LDR-Light-Detection-System
A small light-sensing system using an LDR, LED, and buzzer. When ambient light drops below a set threshold, the LED turns on and the buzzer sounds, alerting the user. This project demonstrates ADC reading, analog sensor processing, and basic automation using microcontrollers.

**Components & Supplies**
Arduino Nano Every
LDR (Light Dependent Resistor)
Active Buzzer
5mm LEDs (various colors)
Jumper wires & breadboard

**Apps & Platforms**
Arduino IDE

**Features**
Measures ambient light with an LDR
Activates LED and buzzer below threshold
Adjustable threshold via Arduino code
Demonstrates basic automation and sensor-to-actuator control

**How It Works**
LDR outputs analog voltage based on light intensity
Arduino reads LDR value using ADC
When light < threshold, LED lights up and buzzer activates
When light >= threshold, LED/buzzer deactivate

**Results**
Successfully detects darkness and triggers alerts
Strengthened understanding of ADC, sensor reading, threshold logic, and microcontroller-based automation
