Automatic control of indoor devices based on environmental parameters
Control system is included to save power by making fans and lights automatically turn on and off with the help of intelligent control system.
Project includes DHT11 sensor, light sensor, flame sensor. Four relays are used to control four respective loads.
Prerequisites:
- PIC C Compiler 
   IDE versions 5.025
- Proteus 8.12 Pro
- PICKIT 3 Programmer version 3.10
Description:
Use PIC16F877A to control relay at preset values, the DHT11 provide temperature and humidity , the LDR sensor send light intensity, digital signal from flame sensor
+ Hum >30 C relay on 
+ Tem >85%  relay on 
+ ADC (0-1024) if it >780 relay on .
+ Fire!!!  relay on .
