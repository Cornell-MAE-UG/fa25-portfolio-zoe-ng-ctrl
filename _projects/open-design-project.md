---
layout: project
title: Open Design Project
description: Open Design Project for MAE 2250, Introduction to Mechanical Design
technologies: [Autodesk Fusion]
image: /assets/images/grapeharvester.png
---


As part of our Open Design Project for MAE 2250: Introduction to Mechanical Design, our team designed a mechanical solution to help reduce the spread of invasive Spotted Lanternflies (SLFs) during grape harvesting.

SLFs can cling to grape crops and enter mechanical harvesters, where even one or two insects can contaminate a batch and make the grapes unsellable. Our project focuses on removing SLFs before the grapes enter the harvester using a compressed-air mechanism mounted to the front of the harvester. This would minimize interference with the harvesting process, reduce labor costs, and tackling the problem at this stage would give us the most control over the removal of SLFs in grape harvesting

Our final concept uses a compressed air canister, a crank-actuated trigger mechanism, and a two-axis gimbal to aim and stabilize the air stream. This page documents our design process, including our three major project milestones: our client pitch, functional prototype, and final client report.


<br><br>

## Table of Contents
- [Client Pitch](#client-pitch)
- [Functional Prototype](#functional-prototype)
- [Client Report](#client-report)

<br><br>

<h2 id="client-pitch">Client Pitch</h2>

Our client pitch introduced the SLF problem, explained why we focused on the harvesting stage, and proposed an early design direction for removing SLFs before they enter the grape harvester.

Here is our client outline/pitch:

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

Here is a drawing of our design and a picture of our prototype:
![Photo of drawing]({{ "/assets/images/prototype-drawing.png" | relative_url }}){: .block-image-l style="width: 550px"}

![Photo of prototype]({{ "/assets/images/IMG_0121.jpg" | relative_url }}){: .block-image-l style="width: 550px"}

<br>

### What was Tested
We tested three main aspects of the prototype.
 
First, we evaluated the trigger actuation mechanism to determine whether it could reliably engage and actuate the compressed-air can trigger with sufficient force. We assessed the shaft–trigger interaction qualitatively by rotating the shaft and observing whether it consistently engaged and depressed the trigger. We also measured the required actuation force using a spring scale and evaluated fit using caliper measurements.

Next, we tested the structural stability of the housing to assess whether the housing and mounting system can securely support the compressed air can and maintain stability during operation. Due to manufacturing constraints, a wooden prototype was used in place of the intended 3D-printed housing. We qualitatively evaluated structural stability, checking for unwanted movement and ensuring that the housing did not interfere with the mechanism’s motion.

Finally, we tested the effectiveness of the air stream to determine whether it was concentrated and forceful enough to displace SLFs at a target distance of 2.5 ft. We used ~1 g proxy targets placed at varying distances from the nozzle and recorded the maximum effective displacement distance.

<br>

### Outcome
Our prototype successfully demonstrated the core functionality of the design: the mechanism was able to actuate the trigger and produce a focused air stream capable of displacing proxy SLF targets. Testing also revealed several limitations in the current iteration. In particular, shaft deflection reduced the efficiency of trigger actuation, and the nozzle orientation limited the effective range of the air stream. As a result, the prototype did not yet achieve our target performance of reliable SLF removal at 0.5 m.

These findings informed the next iteration of our design. Moving forward, we plan to strengthen the shaft to reduce deflection, improve the housing structure for greater stability, and add a 2-axis gimbal mechanism to provide increased aiming and stabilization.

<br>

Here is a more in-depth document describing our functional prototype, the tests we conducted and their respective outcomes:
<iframe src="https://docs.google.com/document/d/e/2PACX-1vS2NqJ4t7ecoCgoWGFFAy-fVEn9Y6wlesh3HlkaAEJi1s5089RL0vjtZFD7dNp6Yxzlsj3Zazw7sxqs/pub?embedded=true" width="100%" height="600px"></iframe>


<h2 id="client-report">Client Report</h2>

Our client report summarizes our final proposed solution, prototype performance, conclusions, and recommended next steps.

### Proposed Solution

Our final design is a harvester-mounted compressed-air removal system. The mechanism releases a concentrated stream of air to blow SLFs off grape plants before the grapes enter the harvester.

The design has two main subsystems:

- **Trigger Actuation System:** A crank handle rotates a 3D-printed shaft, which presses the compressed air canister trigger to release air.
- **Gimbal System:** A two-axis gimbal allows the canister to aim at SLFs and remain stable while mounted on or near the harvester.

Key features include the 3D-printed trigger shaft, acrylic canister housing, crank handle, bearings, and gimbal rings.

<br>

### How It Works / How It Is Used

The compressed air canister is secured inside the acrylic housing. When the user turns the crank handle, the shaft rotates and compresses the canister trigger, releasing a focused air stream. The gimbal allows the canister to rotate and aim toward SLFs on grape vines, helping target the insects before they enter the harvester.

<br>

### Testing Results

Our main testing results were:

- The prototype blew off modelled SLFs weighing around 1 gram at distances of up to 2.5 ft.
- A small air stream required about 25 N of trigger force.
- Full trigger depression required about 45 N of force.
- The 3D-printed shaft successfully reached the target force of 45 N.
- The average time to displace modelled SLFs was 5.49 seconds, which was below our 10-second target.

<br>

### Conclusion and Recommendation

Overall, our prototype is promising. It successfully demonstrated that compressed air can remove modelled SLFs and that the mechanism can be compact enough for future harvester integration.

However, the design is not yet ready for field deployment. We recommend further development before field testing. The next iteration should:

- automate the shaft and gimbal using motors,
- integrate camera or sensor-based SLF detection,
- replace disposable air canisters with a refillable compressed-air system,
- test whether the air stream removes SLFs without also blowing off grapes.

<br>

### Full Client Report

<iframe src="https://docs.google.com/document/d/e/2PACX-1vTN_t1FKzDCe07kXqWNK5rjWPbhUe-iP6KhwJmEwvVDqRvc7b58BFeY-RPgiiWOhybb5NWJZt4iG5BK/pub?embedded=true"></iframe>

