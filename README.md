# Cell Phone Controlled Bot
This project demonstrates how to build a cell phone-controlled robot using Arduino and physical components, such as NodeMCU, that operates over a Wi-Fi connection. The accompanying mobile application is created using MIT App Inventor. By following this guide, you will be able to create your own robot that can be controlled wirelessly from a mobile device.
# Prerequisites
Before you begin, ensure that you have the following:

Arduino board (preferably Arduino Uno)
NodeMCU or any other Wi-Fi enabled microcontroller
Motor driver module (e.g., L293D)
Chassis, motors, and wheels for the robot
Jumper wires and a breadboard
A Wi-Fi-enabled cell phone
USB cable for Arduino programming
USB cable for powering NodeMCU
MIT App Inventor account (https://appinventor.mit.edu)

# Hardware Setup
Connect the Arduino board to your computer using the USB cable.
Mount the NodeMCU on the breadboard and connect it to the computer using another USB cable for power.
Connect the motor driver module to the Arduino board following the wiring diagram for your specific module.
Connect the motors to the motor driver module.
Attach the wheels to the motors and assemble the chassis.
Ensure all connections are secure and double-check the wiring.

# Software Setup
Install the Arduino IDE on your computer (https://www.arduino.cc/en/software).
Open the Arduino IDE and install the necessary libraries for the NodeMCU and motor driver module (refer to the respective library documentation).
Download the Arduino code provided in the repository and open it in the Arduino IDE.
Connect the Arduino board to your computer and upload the code to the Arduino.

# Mobile Application Setup

Go to MIT App Inventor (https://appinventor.mit.edu) and sign in with your account.
Create a new project and open the MIT App Inventor development environment.
Import the provided "CellPhoneControlledRobot.aia" file into your project.
Once imported, you will see the blocks that define the behavior of the app.
Connect your mobile device to the same Wi-Fi network as the NodeMCU.
Click on the "Build" menu and select "App (provide QR code for .apk)" to generate the app.
Scan the QR code with your mobile device to install the app.

# Usage
Ensure that the Arduino and NodeMCU are powered on and connected properly.
Launch the installed app on your mobile device.
Connect your mobile device to the Wi-Fi network created by the NodeMCU.
Once connected, the app will establish a connection with the NodeMCU.
Use the on-screen controls (e.g., buttons, sliders) to control the movement of the robot.
The commands sent from the app to the NodeMCU will be translated into motor movements, allowing you to control the robot wirelessly.

# Acknowledgements
This project is inspired by various Arduino and robotics tutorials available online.
The MIT App Inventor platform provides a user-friendly environment for creating mobile applications without requiring extensive programming knowledge.
