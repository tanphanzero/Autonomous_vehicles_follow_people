# Autonomous_vehicles_follow_people

- Function: Detect and follow people
- Usage: STM32F407 reads the Encoder signal and Jetson Nano reads the signal from the Camera (using Yolov8 to detect people). Based on the position of the person that the Camera reads (left, right, far or close to the vehicle), the desired speed will be given and transmitted to STM32F407. The encoder reads the actual speed of the vehicle and transmits the signal to STM32F407. The microcontroller will rely on the desired speed and actual speed to calculate the PWM pulse width sent to the Motor through the MRAC controller. Use ROSMASTER to manage transmitted and received data

![doan2](https://github.com/tanphanzero/Autonomous_vehicles_follow_people/assets/85573204/2daad9e5-ad65-4ff8-b099-3d067e0ed39b)

![image](https://github.com/tanphanzero/Autonomous_vehicles_follow_people/assets/85573204/8ca1c5f6-9d38-4b10-9a12-f38db396835a)

![image](https://github.com/tanphanzero/Autonomous_vehicles_follow_people/assets/85573204/b4d97525-eb2f-472d-93ec-78b2796f6bbc)

## Information about source code
### Folder source: **catkin_stm32_ws** used on Jetson Nano. **robot** used on STM32F407.
### File source:
* /catkin_stm32_ws/test/src/person_follow.py for Algorithms follow people.
* /catkin_stm32_ws/src/rosserial_python/nodes/serial_node.py for UART signal transmission between Jetson Nano and STM32F407.
* /catkin_stm32_ws/src/alpha/src/xacro/alpha.xacro contains the Robot's hardware parameters for simulation on RViz.
* /catkin_stm32_ws/src/alpha/src/launch/alpha.launch used to run the entire system.

## Video demo

Video demo project: https://youtube.com/shorts/NfBtLsbgUsM
