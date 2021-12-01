
# Requirements

## Introduction

Ultrasonic sensors are great tools to measure distance and detect objects without any actual contact with the physical world. It is used in several applications, like in measuring liquid level, checking proximity and even more popularly in automobiles to assist in self-parking or anti-collision systems. Previously we have also build many Ultrasonic Sensor projects like water level detecting, Ultrasonic Radar etc . This is an efficient way to measure small distances precisely. In this project, we have used the HC-SR04 Ultrasonic Sensor with Atmega328 to determine the distance of an obstacle from the sensor. The basic principle of ultrasonic distance measurement is based on ECHO. When sound waves are transmitted in the environment then waves return back to the origin as ECHO after striking on the obstacle. So we only need to calculate the traveling time of both sounds means outgoing time and returning time to origin after striking on the obstacle. As the speed of the sound is known to us, after some calculation we can calculate the distance.

## Research

Nowadays, we have some difficulties in obtaining the distance that we want to measure. Even though, measuring tape is an easy option, but this kind of tool will have a limitation of manual error. Before this, engineers have produced a range finder module but in the end, they find out the module have many disadvantages like limitation for distance, different result for different coloured obstacles, and need a calibration for every time before starts using it. Manual distance measuring is always done at the expense of human error. Precise and fix measurement of low range distance, is the main objective for this project. .This project is used to measure the distance by using ultrasonic sensors.

## Features and Cost and Timeline

1. Used to measure the obstacle distance.

2. This system used in automotive parking sensors and obstacle warning systems.

3. Used in terrain monitoring robots
         
## Defining Our System

Distance measurement using HC-SR04 and ATMEGA328p. In this project i have measured distance in centimeters, with the help of HC-SR04 Ultrasound sensor, ATMEGA328p micro-controller, LCD Display via I2C bus.

Principle:

Timer2 of ATMEGA328p is used to generate a Trigger pulse of 20uS, the ultrasonic module sends out a 8cycle burst of 40khz which hits the object surface and returns back to raise an echo pulse. The pulse-width of this pulse is proportional to the distance between the module and Object.

Input capture module of the ATMEGA was used to capture the time between rising and falling edges of the echo pulse. The prescaler of this unit was chosen, such that the resolution of pulse-width is 16uS.

The display in use is LCD which has an integrated chip that converts serial data (via I2C bus) into parallel stream of bits for the LCD

## SWOT ANALYSIS

###  Strength:

#### 1. Measure the distance which wil be easy to conﬁgure and handle.

#### 2. Easy to use and reliable

#### 3. cost

#### 4. Technology advantages

###  Weaknesses:

#### 1. They cannot tell you the exact distance or location of the obstacle.

#### 2. Marketing deficiencies

### Opportunities:

#### 1. New technology

#### 3. New markets or services

### Threats:

####  1. New or increased competition

#### 2. Adverse demograghic changes

#### 3. Economic slowdowns

## 4W's and 1'H

WHAT:

Distance is a numerical measurement of how far apart objects or points are.Ultrasonic sensor provides an easy way in distance measurement.

WHY:

Ultrasonic sensors are great tools to measure distance and detect objects without any actual contact with the physical world. It is used in several applications.

WHERE:

Measuring liquid level, checking proximity and even more popularly in automobiles to assist in self-parking or anti-collision systems.

WHEN:
The ultrasonic sensor emits a high-frequency sound pulse and calculates the distance depending upon the time taken by the echo signal to travel back after reflecting from the desired target. The speed of sound is 341 meters per second in air. After the distance is calculated, it will be displayed on the LCD display.
 
How:

This project, we have used the HC-SR04 Ultrasonic Sensor with ATMEGA328 to determine the distance of an obstacle from the sensor. The basic principle of ultrasonic distance measurement is based on ECHO.



## Detail requirements


## Low Level Requirements
| ID | Description | Status (Implemented) |
| --- | --- | --- |
| HR01 |Enable ICP Interrupt | Implemented |
| HR02 |Enable rising edge detection,noise cancellation,| Implemented |
| HR03 |Enable internal pullups on PORTC PINS  SDA(PC4) ,SCL(PC5) | Implemented |
| HR04 | I2C and LCD | Implemented |



## High Level Requirements
| ID | Description | Status (Implemented) |
| --- | --- | --- |
| LR01 |The Timer count (OCR2A) of Timer2 was chosen | Implemented |
| LR02 |Timer2 of ATMEGA328p is used to generate a Trigger pulse of 20uS,  | Implemented |
| LR03 |The prescaler of this unit was chosen, such that the resolution of pulse-width is 16uS. | Implemented |



















         
         
         
