---
layout: project
title: Heat Transfer Device
description: Class project with Graphs
technologies: NA
image: /assets/images/IMG_7518.jpg
---

As part of a Thermodynamics ENGRD 2210 class assignment, we were tasked to analyze a real-world instance of a device or system that we have learned about in this course, explain how it works in detail, and discuss how its performance would change under a change in design or operating conditions. 

I chose to analyze a heat exchanger driven by two pumps. Below is a photo showing the internal structure of the heat exchanger:

![Photo of old radio]({{ "/assets/images/IMG_7519.jpg" | relative_url }}){: .block-image-l style="width: 400px"}

The experimental setup consisted of two water reservoirs. The hot reservoir was a bucket fitted with an immersion heater and pump, while the cold reservoir was a Styrofoam-insulated bucket with a second pump. Water from each reservoir was circulated through the heat exchanger.
Here is a picture of our setup:

![Photo of old radio]({{ "/assets/images/IMG_7524.jpg" | relative_url }}){: .block-image-l style="width: 550px"}

We set and measure the temperature of these two reservoirs to start at around 40 degrees celsius for the hot reservoir, and about 5 degrees celsius for the cold reservoir. We took 3 trials, one where the heat exchanger operated in counter flow with a slower mass flow rate, one where it operated in counter flow with a faster mass flow rate, and one where we operated the heat exchanger in parallel flow with the same faster mass flow rate.
Here are the results that we collected:

![Photo of old radio]({{ "/assets/images/IMG_7526.jpg" | relative_url }}){: .block-image-l style="width: 400px"}

Now, for the analysis. I first compared and analyzed the results from the first and second trial which compared slow counter flow to fast counter flow, to analyze the effect of flow rate:

![Photo of old radio]({{ "/assets/images/trial1-2.jpeg" | relative_url }}){: .block-image-l style="width: 500px"}

From these results, Trial 2 had slightly lower effectiveness (57.9% vs 59.7%) than Trial 1, which makes sense as the faster flow rate gives the hot and cold water less time to exchange heat as they pass through the heat exchanger. However, the higher flow rate in Trial 2 would result in greater total heat transfer rate (W) despite lower efficiency per unit mass. This shows that despite lower effectiveness, having a higher flow rate may still be better for applications that need maximum total heat transfer rather than maximum efficiency.

Now, I analyze Trial 3, comparing fast counter flow to fast parallel flow, to examine the effect of flow configuration at the same high flow rate:

![Photo of old radio]({{ "/assets/images/trial3.jpeg" | relative_url }}){: .block-image-l style="width: 500px"}


Trial 3 showed dramatically lower effectiveness (44.1% vs 57.9%) compared to Trial 2, demonstrating the significant advantage of counter flow over parallel flow configuration. This reduction in effectiveness occurs because in parallel flow (Trial 3), both fluids enter on the same side and flow in the same direction. This causes them to approach similar temperatures by the exit, where the hot drops to 20°C while the cold rises to 16.5°C, leaving only a 3.5°C difference to drive heat transfer at that end. Counter flow (Trial 2) is more effective because the fluids flow in opposite directions, keeping larger temperature differences throughout: the hot inlet (41°C) faces the warm cold outlet (23°C), while the cool hot outlet (17°C) faces the cold inlet (3°C), maintaining good heat transfer along the entire length. This explains why counter-flow designs are strongly preferred in real world applications like HVAC systems despite being slightly more complex to manufacture.


Finally, an energy balance was applied to the heat exchanger to quantify heat loss to the surroundings for each trial. Treating the heat exchanger as a control volume and assuming steady-state operation, no shaft work, and negligible changes in kinetic and potential energy, the general energy balance reduces to a comparison between the enthalpy change of the hot and cold streams

![Photo of old radio]({{ "/assets/images/qloss.jpeg" | relative_url }}){: .block-image-l style="width: 500px"}

The results show a clear trend. Trial 1 exhibited minimal heat loss, indicating near ideal counter flow performance and effective insulation. Trial 2 experienced increased heat loss, likely due to higher flow rate, reduced residence time, and greater experimental uncertainty. Trial 3 showed the largest heat loss by a significant margin, which could likely be due to the lower effectiveness of parallel flow, which leaves more thermal energy in the system available for dissipation to the surroundings. 


![Photo of old radio]({{ "/assets/images/IMG_7518.jpg" | relative_url }}){: .block-image-l style="width: 550px"}


The main limitations of this experiment are the lack of direct mass flow rate measurements and the assumption of steady-state operation. In addition, temperatures were measured manually, which introduces uncertainty, particularly at higher flow rates where the system may not have fully stabilized before measurements were taken.

Overall, this experiment shows how both flow rate and flow configuration affect heat exchanger performance in practice. Counter flow consistently resulted in higher effectiveness and lower heat loss, while increasing the flow rate introduced a trade-off between efficiency per unit mass and total heat transfer. The parallel flow configuration performed the worst, with low effectiveness and significant heat loss. By combining effectiveness calculations with an energy balance, this experiment demonstrates how thermodynamic principles can be used to interpret experimental data and understand non ideal behavior in real engineering systems.

I learned a lot from this experiment seeing how real heat exchangers work and behave differently from ideal models, and I really enjoyed the opportunity to see how the theory we have learnt from class applied to a real system.