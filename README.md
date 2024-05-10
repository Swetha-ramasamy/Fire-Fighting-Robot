# Fire Fighting Robot with Arduino and NodeMCU

## Problem Statement:
Fire disasters pose significant risks, potentially resulting in heavy financial losses and
loss of lives. Challenges such as explosive materials, smoke, and high temperatures can hinder
firefighters' access to fire sites, endangering their lives. In such hazardous environments,
deploying fire-fighting robots proves invaluable. Utilizing IoT technology, our Firefighting robot
aims to autonomously detect and extinguish small flames by navigating to the location. Delays in
firefighter arrival can have dire consequences, underscoring the importance of our robot, which
continually monitors its surroundings and swiftly intervenes to extinguish fires without
hesitation.

## Objective and Scope:
### Objective:
The objective of our firefighting robot project is to enhance firefighting capabilities by
deploying an autonomous robot equipped with IoT technology. This robot aims to detect and
extinguish small flames in hazardous environments, reducing reliance on human intervention and
minimizing the risk to firefighters' lives. By providing swift and efficient responses to fire
incidents, the objective of our prototype is to mitigate financial losses and prevent the loss of
lives associated with fire disasters.
### Scope:
The scope of the project involves designing and implementing an autonomous
firefighting robot equipped with IoT technology. The robot will operate within a predefined
boundary range, detecting and extinguishing small flames within its vicinity. It will utilize
sensors to detect fires and navigate towards them if they are outside its initial range, effectively
responding to fire incidents. Stakeholders can receive real-time notifications once the flame is
detected or extinguished, allowing for prompt monitoring and response. However, it has
limitations in obstacle detection, meaning it may not avoid obstacles in its path. The robot will
operate on a continuous power supply rather than relying on batteries. Overall, the project aims
to enhance firefighting capabilities, reduce human intervention, and mitigate risks associated
with fire disasters. The features of the project can be briefly explained as follows:
- Flame detection system: Integrating the flame detection sensors to identify and locate
fire incidents within the robot's operational range (approximately 50cm).
- Fire extinguishing procedure: Implementing a submersible water pump for
extinguishing fires, that sprays water for a certain amount of time when a flame is
detected within the given range.
- Navigation towards the fire: Developing the robot to navigate autonomously within its
range, ensuring proper directions (left, right, and straight) in response to fire location.
- Actuation mechanism design: Incorporating relays for controlled deployment of water
to extinguish flames.
- Mobile Application and notification management: Creation of a simple interface using
BLYNK IOT for viewing the intensity of the fire in the app interface and enabling
notifications about the fire detection in the range

## Software & Hardware Requirements:
### Software Requirements:
• Arduino IDE
• Blynk – mobile application
### Hardware Requirements:
• Arduino UNO, nodeMCU-esp8266
• 3 IR Flame sensors
• 2 L298N motor driver modules
• Submersible water pump
• Single Channel Relay Module (5v)
• 4 BO Motors (3v -12v)
• Chassis
• Adaptor (12v)
• Switch
• Jump wires
• Servo motor

## Functional Diagram:


<img width="649" alt="image" src="https://github.com/Swetha-ramasamy/Fire-Fighting-Robot/assets/114848572/a37020b2-93a8-41ab-a990-653c2d44aab4">

## Input & Output:
### Arduino UNO output:

<img width="564" alt="image" src="https://github.com/Swetha-ramasamy/Fire-Fighting-Robot/assets/114848572/4873095d-d25a-4bbd-8d21-3334246d68e1">


<img width="294" alt="image" src="https://github.com/Swetha-ramasamy/Fire-Fighting-Robot/assets/114848572/3c6693ef-7acb-4960-a769-481d60bddbb4">


### Blynk mobile application output:



<img width="208" alt="image" src="https://github.com/Swetha-ramasamy/Fire-Fighting-Robot/assets/114848572/fa5b134c-d4b4-4e64-b365-97cb113d068e">


### Alert notification:


<img width="222" alt="image" src="https://github.com/Swetha-ramasamy/Fire-Fighting-Robot/assets/114848572/b9cc45c3-a697-4f32-b452-c1c5657b314e">



## Conclusion:

In conclusion, our firefighting robot project presents a significant advancement in firefighting technology. By deploying an autonomous robot equipped with IoT capabilities, we have addressed the need for swift and efficient responses to fire incidents in hazardous environments. 
While the robot operates within a predefined boundary range and effectively detects and extinguishes fires within this area, it does have limitations, particularly in obstacle detection. However, despite these challenges, the project marks a crucial step forward in
minimizing risks to firefighters' lives and reducing financial losses associated with fire disasters. Moving forward, continued research and development in this field will further enhance the
effectiveness and reliability of autonomous firefighting robots, ultimately improving safety and resilience in the face of fire emergencies. Future enhancements could focus on improving obstacle detection capabilities to enhance the robot's navigation in complex environments. Incorporating machine learning algorithms could enable the robot to learn from past experiences and optimize its firefighting strategies for even greater efficiency and effectiveness.




