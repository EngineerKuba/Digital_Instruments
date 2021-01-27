# Digital_Instruments
Project made for education purpose. 

Microcontroller - stm32f302

Sensors used:
  - L3G4200D - three-axis digital output gyroscope
  - LSM9DS1 - 3D accelerometer, 3D gyroscope, 3D magnetometer
  - HC-SR04 - Ultrasonic Sensor
  - AFBR-S50MV85G - Time-of-Flight Sensor Module for Distance and Motion Measurement
  - OpenLog - simple serial logger 

Servo:
  - 2x SG 90

Goal:
Integrate all the sensors in one system. 

This project aims to build a ‘robot’ of sorts, with a limited number of functions. Mostly, the result will be a proof of concept, attempting to make several different sensors and motors, interface and work with a microcontroller. The goal is to have a device able to do some sort of sweep of an area, and output the distance from a light and an ultrasonic sensor, while at the same time having access to information about its movement from the gyroscopes, accelerometer and magnetometer. 
Ultimately, integrating all of the systems into the functionality of the device would be preferable, but this must be regarded as a secondary priority. 



## Block diagram
![image](https://user-images.githubusercontent.com/78037389/105997131-88756080-60ab-11eb-9c5d-d1d15bc93514.png)
