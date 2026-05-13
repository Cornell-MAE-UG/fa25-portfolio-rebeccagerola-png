---
layout: project
title: Mechatronics Robot Competition
description: Cube Collection Competition
image: /assets/images/robotpic.jpg
---


[Click here for my final report]({{ "/assets/3780.pdf" | relative_url }})!



For my mechatronics class robot competition, I designed and built an autonomous cube-collecting robot that competed head-to-head against an opposing robot in a timed arena challenge. The project required me to take ownership of the full engineering process, from initial concept through final fabrication. I modeled the entire chassis and mechanical assemblies in Autodesk Fusion, iterating on the CAD design to optimize the robot's footprint, weight distribution, and collection mechanism geometry before committing to physical parts. Once the design was finalized, I laser cut the structural components from sheet stock and assembled the chassis by hand, integrating the drivetrain, motors, servos, and cube intake system into a cohesive build. The servos were responsible for actuating the collection mechanism and manipulating cubes once they were captured, giving the robot precise, repeatable control over its end effector. On the electronics side, I wired an Arduino microcontroller to the motor drivers, servos, color sensors, and power distribution, carefully planning the circuit layout to keep signal lines clean and avoid interference. The color sensors played a critical role in the robot's decision-making, allowing it to distinguish target cubes from the surrounding arena, identify scoring zones, and verify successful pickups in real time. I then wrote and tuned the Arduino code in C++ to control drive behavior, drive the servos through their motion profiles, interpret color sensor data, and respond to sensor input dynamically, allowing the robot to navigate the arena, identify and gather cubes, and react to the presence of the competing robot. The project pushed me to integrate mechanical design, electrical engineering, and embedded programming into a single working system, and the head-to-head competition format meant that strategy and reliability were just as critical as raw performance.

