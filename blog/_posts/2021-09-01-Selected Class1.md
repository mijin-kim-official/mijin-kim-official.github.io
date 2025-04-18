---
layout: post
title: Robot Building - Question of architecture in the age of automation
subtitle: CLASS. Advanced Robotics in Architecture. Supervisor, Dr. Hwang Yi
cover-img: /assets/img/Pic1.png
tags: [Automation, Assembly, Robot Arm, KUKA, Parametric Wall, Rhino3D, Grasshopper, Arduino, ]
comments: true
---

&nbsp; &nbsp; Robots, initially developed to handle tasks that are either too difficult or time-consuming for humans, have evolved far beyond simple, repetitive production processes. With continuous advancements in robot hardware and software technologies, they are now capable of performing complex and diverse tasks across various industries. While their presence remains strong in the automotive and manufacturing sectors, robots are increasingly making their mark in fields like design, the arts, and architecture—areas that involve multiple manufacturing technologies and intricate processing stages.
<br/>
&nbsp; &nbsp; Given that architectural form is profoundly shaped by the materials and tools at its disposal, the integration of robots in architecture has the potential to revolutionize spatial design. In this age of automation, robots could usher in new morphological environments characterized by innovative spatial dynamics and possibilities.

<img src="/assets/img/DK2.gif" width="60%" height="60%">{: .mx-auto.d-block :}
<br/>
#### Robot design automation: 6-axis robot building of parametric brick wall
1. Designing a 3D model of a parametric brick wall with Grasshopper script, with multiple curves. Every target (bricks) and gripper should be in the range of the robot work space(Sphere with radius 0.9m). 
2. Save the target points in .csv format. This file contains the information of the target coordinate(x, y, z). 
3. Import the target information into the RoboDK simulation platform. Stack the blocks refer to the origin frame. 
4. Set the simulation events(attach/detach) and digital pulse. 
5. Operating Motoman GP7, check the robot movement and result.
<br/>

<img src="/assets/img/Pic3.png" width="60%" height="60%">{: .mx-auto.d-block :}
<img src="/assets/img/Pic4.png" width="60%" height="60%">{: .mx-auto.d-block :}

<br/>

#### Towards automated design and dynamic build: Detecting red dot and moving the boxes

<img src="/assets/img/Pic2.png" width="60%" height="60%">{: .mx-auto.d-block :}

&nbsp; &nbsp; The robot arm moves toward the target box when the camera sensor, mounted on the end-effector, detects a red dot on the surface of the box. The OpenCV library is used to control the camera sensor, while RoboDK processes these sensor values. As the robot moves, it continuously searches for red dots using the camera, records the sensor data, determines the precise pickup location, and then maneuvers to approach the target.
<br/>
&nbsp; &nbsp; By integrating adaptive self-learning capabilities, this setup marks the initial stage of developing an autonomous construction platform with the robot arm.
<br/>

<img src="/assets/img/Picture14.png" width="60%" height="60%">{: .mx-auto.d-block :}

<br/>
Coursework, Graduate School
<br/>
Supervisor, Dr. Hwang Yi
<br/>
Sep. 2021 - Dec. 2021
<br/>
© Mijin Kim All Rights Reserved
