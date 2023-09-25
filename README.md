# Autonomous_vehicles_follow_people

## Đồ án 2: BK HCM
- Chức năng: Phát hiện và đi theo người
- Sử dụng: STM32F411 đọc tín hiệu Encoder và Jetson Nano đọc tín hiệu từ Camera (sử dụng Yolov8 phát hiện người), truyền xuống STM32F411 và tính toán tốc độ cho Motor thông qua ROSMASTER.

![da2](https://github.com/tanphanzero/Autonomous_vehicles_follow_people/assets/85573204/82d8bea6-b57d-448c-af27-9f1aae96760e)

![image](https://github.com/tanphanzero/Autonomous_vehicles_follow_people/assets/85573204/8ca1c5f6-9d38-4b10-9a12-f38db396835a)

![image](https://github.com/tanphanzero/Autonomous_vehicles_follow_people/assets/85573204/b4d97525-eb2f-472d-93ec-78b2796f6bbc)

- File source: /catkin_stm32_ws/test/src/person_follow.py

**Video demo**

Video demo project: https://youtube.com/shorts/NfBtLsbgUsM
