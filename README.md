
# Project : Intelligent Indoor Environment Control System with Automatic Device Management

**Description**:

This project implements an automated control system for indoor environments, designed to optimize energy consumption while ensuring comfort and safety. The system leverages environmental sensors to monitor temperature, humidity, light intensity, and fire presence. Based on these readings, it intelligently controls connected devices (fans and lights) to maintain a comfortable environment and automatically activate safety measures in case of fire detection.

 **Key Features**:

**Sensor Integration:**

   + DHT11 sensor: Continuously monitors temperature and humidity levels.
   
   + Light-dependent resistor (LDR): Detects ambient light intensity.
   
   + Flame sensor: Provides a digital signal for fire detection.

Smart Control Logic:
Automated fan activation: Triggers based on pre-defined temperature thresholds (>30°C) for energy-efficient climate control.
Adaptive humidity management: Enables humidity-driven activation (Hum > 85%) to regulate moisture levels.
Light-based illumination control: Employs the LDR sensor's ADC value (>780, corresponding to a specific light intensity threshold) to operate lights, minimizing unnecessary power usage.
Emergency response (Fire!!!) 

Note: It is possible to change the threshold value based on the code

**Hardware Requirements:**
+ Microcontroller: PIC16F877A
+ Relays
+ DHT11 sensor
+ Flame Sensor
+ LDR sensor
+ PicKit 3 
etc...

**Software Requirements:**

+ PIC C Compiler IDE (version 5.025 recommended for compatibility)
+ Proteus 8.12 Pro for simulation and debugging
  
**Project Image**:
