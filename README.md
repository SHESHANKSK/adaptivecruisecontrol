
<center><h1>AUTOMOTIVE ELECTRONICS</h1></center>

## COURSE PROJECT: DESIGN A ADAPTIVE CRUISE CONTROL SYSTEM
---
### <center>Project Associates</center>
| Name      | USN | Contact Info    |
| :---       |    :----:   |          ---: |
| Ranjita Gaddanakeri      | 01FE19BEE038       | Here's this   |
| Shubham Kumar Gupta  | 01FE19BEE030        | And more      |
| Priyanka Inamati      | 01FE19BEE050       | Here's this   |
| Sheshank Shyam Kindalkar   | 01FE19BEE049        | And more      |

## 1. Abstract

## 2. Introdution
---

&emsp; &emsp; ACC is an extension of conventional cruise control systems. An ACC system is a driver convenience feature designed to maintain a set following distance from the vehicle ahead. ACC is not a collision warning or avoidance system. An ACC system is designed to assist the driver and is not a fully independent driving system. As with conventional cruise control system manual inputs from the driver, both to accelerator and brake, take priority over the ACC system

&emsp; &emsp;The concept of assisting driver in the task of longitudinal vehicle control is known as cruise control. Starting from the cruise control devices of the seventies and eighties, now the technology has reached cooperative adaptive cruise control. This paper will address the basic concept of adaptive cruise control and the requirement to realize its improved versions including stop and go adaptive cruise control and cooperative adaptive cruise control. The conventional cruise control was only capable of maintaining a set speed by accelerating or decelerating the vehicle.

&emsp; &emsp;Adaptive cruise control devices are capable of assisting the driver to keep a safe distance from the preceding vehicle by controlling the engine throttle and brake according to the sensor data about the vehicle. Most of the systems use RADAR as the sensor, a few uses LIDAR also. Controller includes the digital signal processing modules and microcontroller chips specially designed for actuating throttle and brake. The stop and go cruise control is for the slow and congested traffic of the cities where the traffic may be frequently stopped.

## 3. Litreature Survey


## 4. Operation principle of adaptive cruise control
---
&emsp; &emsp; An LIDAR sensor is usually at the core of the adaptive cruise control (ACC). Installed at the front of the vehicle, the system permanently monitors the road ahead. As long as the road ahead is clear, ACC maintains the speed set by the driver. If the system spots a slower vehicle within its detection range, it gently reduces speed by releasing the accelerator or actively engaging the brake control system. If the vehicle ahead speeds up or changes lanes, the ACC automatically accelerates to the driver’s desired speed.
&emsp; &emsp; Standard ACC can be activated from speeds of around 30 km/h (20 mph) upwards and supports the driver, primarily on cross-country journeys or on freeways. The ACC stop & go variant is also active at speeds below 30 km/h (20 mph). It can maintain the set distance to the preceding vehicle even at very low speeds and can decelerate to a complete standstill. If the vehicle has automatic transmission, and the traffic hold-up is only brief, ACC stop & go can set the vehicle in motion once again. When the vehicle remains stopped longer, the driver needs only to reactivate the system, for example by briefly stepping on the gas pedal to return to ACC mode. In this way, ACC stop & go supports the driver even in heavy traffic and traffic jams.
Since ACC is a comfort and convenience system, brake interventions and vehicle acceleration only take place within defined limits. Even with ACC switched on, it remains the driver’s responsibility to monitor the speed and distance from the vehicle in front.
&emsp; &emsp; To increase comfort and safety of this function, a multipurpose camera can be installed in addition to the LIDAR sensor. By this, for instance, ACC can, thanks to the lateral measuring accuracy of the multi-purpose camera, detect a vehicle entering the driver’s own lane – either planned or unplanned – much earlier, enabling the system to respond more dynamically. For a better and more robust understanding of the scene, data of the LIDAR sensor and the camera can be merged.

## 3. Components of ACC System
---
1. A sensor (LIDAR or RADAR) usually kept behind the grill of the vehicle to obtain the information regarding the vehicle ahead. The relevant target data may be velocity, distance, angular position or lateral acceleration.
   
2. Longitudinal controller which receives the sensor data and process it to generate the commands to the actuators of brakes throttle or gear box using Control Area Network (CAN) of the vehicle




## 4. Advantages and Disadvantages of the ACC System
---
### Advantages
#### System Benifits for Drivers
1.	Comfortable and relaxed driving – even in heavy traffic and traffic jams
2.	Supports the driver in maintaining a safe distance
3.	Allows harmonious, fuel-efficient traffic flow on the roads
4.	Reduces the risk of rear-end collisions
5.	Driver is better able to concentrate on the current traffic situation

#### System Benifits for Manufactures
1.	Decreases fuel consumption by up to 10 percent
2.	Reduces rear-end collisions and eases the driving task
3.	Solutions available for cross-country journeys and on freeways as well as in dense urban traffic

### Disadvantages
1. A cheap version is not yet realized.
2. A high market penetration is required if a society of intelligent vehicles is to be formed.
3. Encourages the driver to become careless. It can lead to severe accidents if the system is malfunctioning.
4. The ACC systems evolved till now only enable vehicles to cooperate with the other vehicles but do not respond directly to the traffic signals.


## 6. Workflow
### Existing Method:
The earliest variants of the cruise control system were actually in use even before the automobile creation. The conventional Cruise  control system automatically controls the speed of the car. The speed of the car will be set by the driver by adjusting the throttle position. 
In the cruise control system there is a speed limiter function that will work only for the predefined speed beyond that it will not work. 
However as the number of car increases on-road the conventional cruise control system is becoming obsolete.

### Proposed Method:
The advanced method of the cruise control system is the Adaptive Cruise Control system (ACC). ACC is the system which not only maintains the speed of the car but also measures the distance between vehicle ahead of it and accordingly it will set the speed and keep the vehicle in one track. It also sends the location of the vehicle if any misfortune occurs, as an enhanced feature of the Black Box System. Fuel economy is improved by an adaptive cruise control system.
Our project aims to achieve a cost-effective, user-friendly system that fulfills the basic requirement of Adaptive Cruise Control (speed and distance observation and control) and Black Box (Security of the Driver by sending its location as a text message in case of emergencies). 

The Internet of Things (IoT) based approah to design an adapative cruise control system

#### Workflow





## Refrences

[1] Sankar, Vishnu. "Review on adaptive cruise control in automobiles." International Journal of Mechanical Engineering and Robotics Research 3.2 (2014): 404.

[2] Kumar, Rohan, and Rajan Pathak. "Adaptive cruise control-towards a safer driving experience." International Journal of Scientific and Engineering Research 3.8 (2012): 3-7.

[3] Pagey, K., R. D. Komati, S. Paliwal & S. Lukde “Adaptive Cruise Control System.” International Journal of Creative Research Thoughts 8.0 (2020):1551.0–1560.0.

[4] "Adaptive cruise control for passenger cars" . Bosch Mobility Solutions, 2022 , www.bosch-mobility-solutions.com/en/solutions/assistance-systems/adaptive-cruise-control/
