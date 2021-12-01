# M2-Embedded_Distance_measurement
[![Codacy Badge](https://app.codacy.com/project/badge/Grade/f7843562e5a3403ebaaa1607d56e354b)](https://www.codacy.com/gh/VASANTHAKUMAR8/M2-Embedded_Distance_measurement/dashboard?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=VASANTHAKUMAR8/M2-Embedded_Distance_measurement&amp;utm_campaign=Badge_Grade)
[![Cppcheck](https://github.com/VASANTHAKUMAR8/M2-Embedded_Distance_measurement/actions/workflows/cppcheck.yml/badge.svg)](https://github.com/VASANTHAKUMAR8/M2-Embedded_Distance_measurement/actions/workflows/cppcheck.yml)
[![Build](https://github.com/VASANTHAKUMAR8/M2-Embedded_Distance_measurement/actions/workflows/compile.yml/badge.svg)](https://github.com/VASANTHAKUMAR8/M2-Embedded_Distance_measurement/actions/workflows/compile.yml)


## Introduction

Ultrasonic sensors are great tools to measure distance and detect objects without any actual contact with the physical world. It is used in several applications, like in measuring liquid level, checking proximity and even more popularly in automobiles to assist in self-parking or anti-collision systems. Previously we have also build many Ultrasonic Sensor projects like water level detecting, Ultrasonic Radar etc . This is an efficient way to measure small distances precisely. In this project, we have used the HC-SR04 Ultrasonic Sensor with Atmega328 to determine the distance of an obstacle from the sensor. The basic principle of ultrasonic distance measurement is based on ECHO. When sound waves are transmitted in the environment then waves return back to the origin as ECHO after striking on the obstacle. So we only need to calculate the traveling time of both sounds means outgoing time and returning time to origin after striking on the obstacle. As the speed of the sound is known to us, after some calculation we can calculate the distance.




## Folder Structure
Folder               | Description
-------------------  | -----------------------------------------
`1_Requirements`     | Documents Detailing requirements and research.
`2_Design_diagram`     | Documents Specifying design details.
`3_Implementation`   | All Code and Documentation.
`4_TestPlan`| Test Cases.
