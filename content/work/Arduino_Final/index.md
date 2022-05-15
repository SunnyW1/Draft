---
title: Advanced Physics Lab 3 Learning PID Control Loops
date: 2022-05-09 02:46:42
category: tech
tags:
keywords:
---


# Learning PID Control Loops with the Arduino Uno

Creating a data acquisition system that responds to external changes is essential for regulation and ensuring steady state conditions. Automatic self-regulating systems play a vital role in both the real world and in laboratory settings. A proportional–integral–derivative (PID) controller is a widely used method of self-regulation as it is a robust method for calculating error and, subsequently, determining an appropriate response. To explore the PID controller capabilities of the Arduino Uno, I implement a magnetic levitation device where the distance of the suspended magnet is maintained using a PID algorithm. In this project, the current going through the electromagnet is adjusted to stabilize hall sensor measurements. By stabilizing the hall sensor measurements, the magnetic field strength produced by the electromagnet is regulated, and the distance of the suspended magnet is controlled. The output voltages from the hall sensor is recorded for two systems. In the first system, error is determined by taking the difference between the current reading and a set threshold. In the second, error is calculated through a PID algorithm. The desired the hall sensor voltage is set to 2.2V, and both systems achieve an average of (2.199±0.006)V over a period of one minute. As a result of the PID implementation, the the range of voltages from the hall sensor is reduced from 0.049V from the first method to 0.011V.

# Video Presentation

{{< rawhtml >}}

<video width="520" height="440" controls>
  <source src="Final.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>

{{< /rawhtml >}}
