# Lab 7-1: Local Component Demo

## คำอธิบาย
การทดลองนี้แสดงการใช้งาน component ที่มีอยู่ในโฟลเดอร์ `components/Sensors/` ของ project


## สรุปคำสั่งที่ใช้ และผลลัพธ์ที่ได้

<เขียนตอบในนี้>
1.cd lab7-1_Managed_Local_Component
2.. $IDF_PATH/export.sh
3.idf.py set-target esp32
4.idf.py build
5.idf.py qemu monitor

## ผลลัพธ์
I (11494) SENSOR: 📊 Reading sensor data from file: /project/components/Sensors/sensor.c, line: 18
I (11494) SENSOR: 🌡️  Temperature: 31.0°C
I (11494) SENSOR: 💧 Humidity: 70.0%
I (11494) SENSOR: ✅ Sensor status check from file: /project/components/Sensors/sensor.c, line: 30
I (11494) SENSOR: 📈 All sensors operating normally
I (11494) LAB7-1: ----------------------------
I (14494) SENSOR: 📊 Reading sensor data from file: /project/components/Sensors/sensor.c, line: 18
I (14494) SENSOR: 🌡️  Temperature: 33.6°C
I (14494) SENSOR: 💧 Humidity: 89.4%
I (14494) SENSOR: ✅ Sensor status check from file: /project/components/Sensors/sensor.c, line: 30
I (14494) SENSOR: 📈 All sensors operating normally
I (14494) LAB7-1: ----------------------------
I (17494) SENSOR: 📊 Reading sensor data from file: /project/components/Sensors/sensor.c, line: 18
I (17494) SENSOR: 🌡️  Temperature: 29.1°C
I (17494) SENSOR: 💧 Humidity: 88.9%
I (17494) SENSOR: ✅ Sensor status check from file: /project/components/Sensors/sensor.c, line: 30
I (17494) SENSOR: 📈 All sensors operating normally
I (17494) LAB7-1: ----------------------------