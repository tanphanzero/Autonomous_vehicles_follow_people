# Autonomous_vehicles_follow_people

- Function: Detect and follow people
- Usage: STM32F411 reads the Encoder signal and Jetson Nano reads the signal from the Camera (using Yolov8 to detect people), transmits it to STM32F411 and calculates the speed for the Motor through ROSMASTER.

![da2](https://github.com/tanphanzero/Autonomous_vehicles_follow_people/assets/85573204/82d8bea6-b57d-448c-af27-9f1aae96760e)

![image](https://github.com/tanphanzero/Autonomous_vehicles_follow_people/assets/85573204/8ca1c5f6-9d38-4b10-9a12-f38db396835a)

![image](https://github.com/tanphanzero/Autonomous_vehicles_follow_people/assets/85573204/b4d97525-eb2f-472d-93ec-78b2796f6bbc)

- File source: /catkin_stm32_ws/test/src/person_follow.py

**Video demo**

Video demo project: https://youtube.com/shorts/NfBtLsbgUsM
