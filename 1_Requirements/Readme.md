# REQUIREMENTS
## Introduction
### Ultrasonic sensors are great tools to measure distance and detect objects without any actual contact with the physical world. It is used in several applications, like in measuring liquid level, checking proximity and even more popularly in automobiles to assist in self-parking or anti-collision systems. This is an efficient way to measure small distances precisely. In this project, I have used the HC-SR04 Ultrasonic Sensor with Atmega328 to determine the distance of an obstacle from the sensor. The basic principle of ultrasonic distance measurement is based on ECHO. When sound waves are transmitted in the environment then waves return back to the origin as ECHO after striking on the obstacle. So, only need to calculate the traveling time of both sounds means outgoing time and returning time to origin after striking on the obstacle. As the speed of the sound is known to us, after some calculation calculate the distance. I am going to use this same technique for this distance measurement project.
## Features of the Ultrasonic Sensor Module
#### In this project I have used the HC-SR04 to measure distance in range of 2cm-400cm with an accuracy of 3mm. The sensor module consists of an ultrasonic transmitter, receiver and control circuit. The working principle of ultrasonic sensor is as follows:
- High level signal is sent for 10us using Trigger.
- The module sends eight 40 KHz signals automatically, and then detects whether pulse is received or not.
- If the signal is received, then it is through high level. The time of high duration is the time gap between sending and receiving the signal.
- Specifications : Power Supply: +5V DC; Quiescent Current : <2mA; Working Current: 15mA; Effectual Angle: <15°; Ranging Distance : 2cm – 400 cm/1″ – 13ft; Resolution : 0.3 cm; Measuring Angle: 30 degree; Trigger Input Pulse width: 10uS; Dimension: 45mm x 20mm x 15mm
## SWOT Analysis
#### Strengths
- It has sensing capability to sense all the material types.
- This sensor is not affected due to atmospheric dust, rain, snow etc.
- It can work in any adverse conditions.
- It has higher sensing distance (in centimeters and inches) compare to inductive/capacitive proximity sensor types.
- It provides good readings in sensing large sized objects with hard surfaces.
#### Weaknesses
- It is very sensitive to variation in the temperature.
- It has more difficulties in reading reflections from soft, curved, thin and small objects.
#### Opportunities
- They have greater accuracy than many other methods at measuring thickness and distance to a parallel surface.
- Their high frequency, sensitivity, and penetrating power make it easy to detect external or deep objects.
#### Threats
- Limited testing distance
- Inaccurate readings
- Inflexible scanning methods
## 4W's and 1'H
#### Who :
The importance of the project is calculating accurate distance from any obstacle that we want to measure. Ultrasonic sensors are used primarily as proximity sensors. They can be found in automobile self-parking technology and anti-collision safety systems.

#### What :
As the name indicates, ultrasonic sensors measure distance by using ultrasonic waves. The sensor head emits an ultrasonic wave and receives the wave reflected back from the target. Ultrasonic Sensors measure the distance to the target by measuring the time between the emission and reception.

#### When :
Ultrasonic sensors can measure the distance to a wide range of objects regardless of shape, color or surface texture. They are also able to measure an approaching or receding object. By using “non-contact” ultrasonic sensors, distances can be measured without damage to the object.

#### Where :
The device can be used in many different fields and categories like distance calculation in construction field, robots, car sensor to avoid obstacles and many other applications.

#### How :
Ultrasonic sensors are useful for measuring distances. Ultrasonic waves are transmitted and whenever these strike an obstacle and return back in the from of an echo. Difference of outgoing sound and returning echo gives us the distance.

## Detail Requirements
#### High Level Requirements
- The high-level signal is sent to 10 microseconds using Trigger
- The module sends 40 KHz signals automatically and then detects whether the pulse is received or not through Echo	
- Capable of measuring a distance of up to 400 cm	
- It can be further enhanced by implementing improvements especially in its accuracy and portability	
#### Low Level Requirements
- Suitable for close range detection up to ten meters	
- Provide multiple range measurements per second	




