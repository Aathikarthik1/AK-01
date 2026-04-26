# AK-01
AK-01 is a desktop robotic arm that picks up objects from a table using voice commands and a camera. Say "pick up the bottle" and it finds the object, calculates where it is, and grabs it.
It runs on a Raspberry Pi 4 with a camera module for vision, YOLOv8 nano for object detection, and Vosk for offline speech recognition — no internet needed. Five servo motors handle the movement, controlled over I2C through a PCA9685 driver. A small OLED shows the arm's current status.
Unlike most hobby arms that require manual joystick control, the AK-01 is fully voice-driven, with real-time ML inference running entirely on-device — all custom-designed hardware, firmware, and a 3D-printed structure.
