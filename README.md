# Autonomous_vehicles_follow_people

- Function: Detect and follow people
- Usage: STM32F407 reads the Encoder signal and Jetson Nano reads the signal from the Camera (using Yolov8 to detect people). Based on the position of the person that the Camera reads (left, right, far or close to the vehicle), the desired speed will be given and transmitted to STM32F407. The encoder reads the actual speed of the vehicle and transmits the signal to STM32F407. The microcontroller will rely on the desired speed and actual speed to calculate the PWM pulse width sent to the Motor through the MRAC controller. Use ROSMASTER to manage transmitted and received data

![da2](https://github.com/tanphanzero/Autonomous_vehicles_follow_people/assets/85573204/82d8bea6-b57d-448c-af27-9f1aae96760e)

![image](https://github.com/tanphanzero/Autonomous_vehicles_follow_people/assets/85573204/8ca1c5f6-9d38-4b10-9a12-f38db396835a)

![image](https://github.com/tanphanzero/Autonomous_vehicles_follow_people/assets/85573204/b4d97525-eb2f-472d-93ec-78b2796f6bbc)

- File source: /catkin_stm32_ws/test/src/person_follow.py

**Video demo**

Video demo project: https://youtube.com/shorts/NfBtLsbgUsM
