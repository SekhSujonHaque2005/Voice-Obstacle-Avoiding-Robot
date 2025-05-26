# Voice-Obstacle-Avoiding-Robot

Project Overview:
The Voice + Obstacle Avoiding Robot is an autonomous robotic system designed for intuitive human-robot interaction and safe navigation. Built using Arduino UNO R3, it responds to voice commands for movement control and uses ultrasonic sensors to detect and avoid obstacles. The robot integrates speech recognition and real-time sensor processing, making it ideal for dynamic environments.


Features:
Voice Command Recognition: Processes voice inputs for movement control (e.g., forward, backward, stop).
Obstacle Avoidance: Uses ultrasonic sensors to detect and navigate around obstacles.
Autonomous Navigation: Combines sensor data and algorithms for smooth movement.
Real-Time Feedback: Provides status updates via LED indicators or optional Bluetooth communication.
Low-Cost Design: Built with affordable components like Arduino UNO and HC-SR04 sensors.

Hardware Requirements:
Arduino UNO R3 (clone)
Ultrasonic Sensor (HC-SR04)
L298N Motor Driver
Microphone Module (e.g., KY-038 or similar)
DC Motors with Wheels
Robot Chassis
Bluetooth Module (HC-05, optional for voice input)
LED Indicators
Battery Pack (e.g., 9V or 12V)

Software Requirements:
Arduino IDE
Speech Recognition Library (e.g., Arduino Voice Recognition Module or software-based via Bluetooth)
C/C++ (for programming)
Optional: Mobile app for Bluetooth voice commands

Setup Instructions::
Hardware Assembly:
Mount ultrasonic sensor, microphone module, and motors on the chassis.
Connect components to Arduino UNO via the L298N motor driver.
Attach LED indicators and optional HC-05 Bluetooth module.
Power the system with a battery pack.


Voice Recognition Setup:
Configure the microphone module or HC-05 for voice input.
Program predefined voice commands (e.g., "move forward", "stop") using a speech recognition library.


Obstacle Detection Logic:
Write Arduino code to read ultrasonic sensor data and adjust motor speeds to avoid obstacles.


Integration:
Combine voice control and obstacle avoidance logic, prioritizing obstacle avoidance for safety.
Upload the final sketch to the Arduino UNO.


Testing and Deployment:
Test the robot in a controlled environment with obstacles and voice commands.
Deploy in a real-world setting, monitor performance, and refine as needed.



Webpage Documentation:
The project includes a responsive webpage built with HTML, Tailwind CSS, and JavaScript.
Features a multilingual interface (English, Bengali, Hindi, Punjabi, Bhojpuri, Telugu, Malayalam, Tamil, Marathi).
Includes a contact form powered by Web3Forms API for user inquiries.
Access the webpage here (replace with actual URL if hosted).

Usage:
Power on the robot and ensure all components are functional.
Issue voice commands (e.g., "move forward", "stop") via the microphone or Bluetooth app.
The robot navigates autonomously, avoiding obstacles using ultrasonic sensors.
Monitor LED indicators for status updates.
Visit the webpage for project details, gallery, and to contact the developer.

Contributing:
Contributions are welcome! Please fork the repository, make changes, and submit a pull request. For major changes, open an issue to discuss your ideas.


License:
This project is licensed under the MIT License. See the LICENSE file for details.


Contact:
For inquiries, use the contact form on the project webpage or reach out via email at [sksujonhaque@gmail.com].


© 2025 Sujon | Lovely Professional University
