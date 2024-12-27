# AWS-IoT-Robot

![robot-and-remote](https://github.com/user-attachments/assets/c58830f0-d05e-408f-9d0f-1def5f79a1c7)

# Introduction

This AWS IoT Robot involves creating a Raspberri-Pi robot with AWS IoT and AWS Greengrass.
This project includes web application to control the robot and physical robot construction, showcasing capabilities of AWS IoT services.

# Hardware Requirements

+ Raspberry Pi 3/4
+ Raspberry Pi camera module
+ 1 x 32GB Micro-SD card
+ 2 x 28BYJ-48 Stepper Motor
+ 2 x ULN2003 Motor Driver Board
+ 2 x SG90 servos
+ 1 x HC-SR04 ultra-sonic proximity detector
+ 5v battery pack / power bank with USB output
+ Breadboard
+ Breadboard power supply
+ 3/4 inch Ball caster (similar to Pololu ball caster)
+ Nylon M3 standoffs (for mounting PCBs)

# AWS Services Involved

+ AWS IoT Core
  - Facilitates communication between robot and remot using MQTT protocols.
  - Manage Secure certificate-based authentication.

+ AWS Greengrass (v2)
  - Manages edge computing capabilities on the Raspberry Pi.
  - Deploys Lambda functions for robot operations.

+ AWS Lambda
  - Serverless functions for controlling the robot’s movements

+ Amazon Cognito
  - Provides user authentication and access control for the web application.

+ Amazon Kinesis (WebRTC)
  - Streams live video feed from the robot’s camera to the web application.

+ AWS CloudFormation
  - Simplifies deployment of IoT-specific resources and infrastructure.

+ AWS IAM (Identity and Access Management)
  - Manages roles and permissions required for operations.
