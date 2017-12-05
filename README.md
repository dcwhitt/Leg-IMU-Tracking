# Leg-IMU-Tracking
Repository for work on developing a 2 inertial measurement unit (IMU) system for tracking the angle of a joint.

This code incorporates 2 BNO055 imu sensors and follows the advice found at: 
https://learn.adafruit.com/adafruit-bno055-absolute-orientation-sensor/arduino-code


CONNECTING BNO055 IMU TO ARDUINO:
To connect the assembled BNO055 breakout to an Arduino Uno, follow the wiring diagram below:
  Connect Vin to the power supply, 3-5V is fine. Use the same voltage that the microcontroller logic is based off of. For most Arduinos,        that is 5V
  Connect GND to common power/data ground
  Connect the SCL pin to the I2C clock SCL pin on your Arduino. On an UNO & '328 based Arduino, this is also known as A5, on a Mega it is     also known as digital 21 and on a Leonardo/Micro, digital 3
  Connect the SDA pin to the I2C data SDA pin on your Arduino. On an UNO & '328 based Arduino, this is also known as A4, on a Mega it is        also known as digital 20 and on a Leonardo/Micro, digital 2
  
  RETRIEVING DATA FROM IMUs:
  DOWNLOAD THE ADAFRUIT UNIFIED SENSOR SYSTEM
  Allows you to retrieve orientation data in a standard data format.
  https://learn.adafruit.com/using-the-adafruit-unified-sensor-driver/introduction
  
