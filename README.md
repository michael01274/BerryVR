# BerryVR
-IMU trackers for VR using Raspberry PI!-

BerryVR Intro:
BerryVR is an innovative virtual reality full body tracking (FBT) system that harnesses the power of a Raspberry Pi Pico combined with an inertial measurement unit (IMU). Although this forms the cornerstone of the technology, BerryVR offers a gateway that goes beyond these basic components.

  Why use a Raspberry Pi?
   Using a Raspberry Pi instead of an ESP32 has many benefits, such as it supports additional interfaces, including 2 × I2C, 2 × SPI, 16 × PWM channels, and 2 × UART. Another reason I chose the Raspberry PI Pico is that it has 40 pins! (26 are GPIO). this means it will have more room for more sensors! Also to note is the power consumption The Pico uses 91mA while the ESP32 uses more than 100 mA. Now, I know the ESP32 has its benefits but we all have our preferences. 


  What IMUs/Sensors are used?
    As of now, the BMI160 is the main IMU that will be used. I'm still working on making it compatible with other IMUs, but we all need to start somewhere. 

  ![alt text](https://github.com/michael01274/BerryVR/blob/main/BerryVR.png?raw=true) 

