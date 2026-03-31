---
layout: project
title: Open Design Project
description: Open Design Project for MAE 2250, Introduction to Mechanical Design
technologies: [Autodesk Fusion]
image: /assets/images/grapeharvester.png
---

As part of our Open Design Project for MAE 2250: Introduction to Mechanical Design, we are tasked with developing a mechanical design to address the problem of invasive Spotted Lanternflies (SLF) damaging agricultural crops, particularly grape vineyards.

Our approach focuses on the harvesting stage, where conditions offers the greatest control over SLF removal. We designed a compressed air canister system mounted to the front of the harvester to identify SLFs and deploy air to remove them before the grapevines are shaken.

This page documents our design process, including our client pitch, functional prototype, testing, and key outcomes.

<br><br>

## Table of Contents
- [Client Pitch](#client-pitch)
- [Functional Prototype](#functional-prototype)

<br><br>

<h2 id="client-pitch">Client Pitch</h2>

Here is our client outline/pitch for our Open Design Project tackling the removal of Spotted Lanternflies during grape harvesting:

<iframe src="https://docs.google.com/document/d/e/2PACX-1vRhUdqWu9RVjenRHZIrhPu8TpY6T2tYA-HOwbH7CR6nJ0UXd8kRjf_16qlmTsXqfFgEmePHeffpiS8o/pub?embedded=true" width="100%" height="600px"></iframe>

<br><br>

<h2 id="functional-prototype">Functional Prototype</h2>

<br>

### Purpose
The purpose of our prototype was to test whether our mechanism could reliably actuate a compressed air canister to produce a controlled air stream capable of removing spotted lanternflies during harvesting.

Our design consists of: 

- 8 oz. Disposable Any Angle Spray Duster 
- 2x 8mm Shaft Steel Flanged Ball Bearing
- Zinc Unthreaded Through-Hole-Mount Crank Handle
- Shaft and Trigger Compresser 
- Outer housing for shaft
- Bracket for Mounting the Angle Spray Duster

Here is a drawing of our design and a picture of the functional prototype:
![Photo of drawing]({{ "/assets/images/prototype-drawing.png" | relative_url }}){: .block-image-l style="width: 550px"}

![Photo of prototype]({{ "/assets/images/IMG_0121.jpg" | relative_url }}){: .block-image-l style="width: 550px"}


### What was Tested
We tested three main aspects of the prototype.
 
First, we evaluated the trigger actuation mechanism to determine whether it could reliably engage and actuate the compressed-air can trigger with sufficient force. We assessed the shaft–trigger interaction qualitatively by rotating the shaft and observing whether it consistently engaged and depressed the trigger. We also measured the required actuation force using a spring scale and evaluated fit using caliper measurements.

Next, we tested the structural stability of the housing to assess whether the housing and mounting system can securely support the compressed air can and maintain stability during operation. Due to manufacturing constraints, a wooden prototype was used in place of the intended 3D-printed housing. We qualitatively evaluated structural stability, checking for unwanted movement and ensuring that the housing did not interfere with the mechanism’s motion.

Finally, we tested the effectiveness of the air stream to determine whether it was concentrated and forceful enough to displace SLFs at a target distance of 0.5 m. We used ~1 g proxy targets placed at varying distances from the nozzle and recorded the maximum effective displacement distance.


### Outcome
Our prototype successfully demonstrated the core functionality of the design: the mechanism was able to actuate the trigger and produce a focused air stream capable of displacing proxy SLF targets. Testing also revealed several limitations in the current iteration. In particular, shaft deflection reduced the efficiency of trigger actuation, and the nozzle orientation limited the effective range of the air stream. As a result, the prototype did not yet achieve our target performance of reliable SLF removal at 0.5 m.

These findings informed the next iteration of our design. Moving forward, we plan to strengthen the shaft to reduce deflection, improve the housing structure for greater stability, and adjust the nozzle orientation to enhance both range and targeting accuracy.

Here is a more in-depth document describing our functional prototype, the tests we conducted and their respective outcomes:
<iframe src="https://docs.google.com/document/d/e/2PACX-1vS2NqJ4t7ecoCgoWGFFAy-fVEn9Y6wlesh3HlkaAEJi1s5089RL0vjtZFD7dNp6Yxzlsj3Zazw7sxqs/pub?embedded=true" width="100%" height="600px"></iframe>