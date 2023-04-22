# Internet of Things Project

## Autonomous IoT-based Sorting Machine

In this project, we intend to prototype a sorting machine which is fully autonomous using IoT. This Project comprises a rotating conveyor belt. Its movement is executed using an ESP32-WROOM-32 microcontroller that pauses and resumes a DC motor attached to the belt. We have used the ESP32-S2-Kaluga-1 Kit v1.3 which has a ESP- LyraP-CAM, which functioned as our main sensor, and an ESP32-S2-WROVER microcontroller, which we used to transmit the captured image of the packages to the cloud. We have also used an ultrasonic sensor to sense the arrival of a new package so we can pause the conveyor belt and let the cloud communication and colour detection happen.