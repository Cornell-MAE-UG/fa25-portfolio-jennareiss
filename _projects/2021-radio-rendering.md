---
layout: project
title: Linear Actuator Mechanism Design
description: linear actuator mechanism design
technologies: [hand drafting]
image: /assets/images/Cover.png
---

For my Statics and Mechanics of Solids course, we were prompted to design a mechanism involving only a linear actuator and a rigid bar in order to lift as much weight as possible to the tallest height within a design space of 0.5m x 1.5m. We were able to utilize a bar of any length, as well as three pin supports of which two needed to be mounted to the ground.

![Lowered configuration]({{ "/assets/images/Loweredconfig.jpg" | relative_url }}){: .inline-image-r style="width: 300px"}

For my linear actuator model, I chose the IMA55 RN05 because it has a large peak thrust force (35.81kN) and a stroke of .1542m to .4572m, which is close to the maximum vertical height of 0.5m. The IMA55 RN05 also has a width of 0.1436m at the base and a rod diameter of 0.05713m.

![Raised configuration]({{ "/assets/images/Raisedconfig.jpg" | relative_url }}){: .inline-image-l }

For my mechanism, I decided to design a lever system with the rigid bar acting as the lever. I chose a length of 1.5m for the bar to maximize its length while ensuring it didn't cross the 1.5m width limit when it was lowered. I set the bar's maximum height to be at the limit of 0.5m. I calculated the horizontal distance the bar would be occupying while at its maximum height to determine where the linear actuator needed to be placed. I then set up a torque balance to solve for the maximum weight that the mechanism could lift, which came out to be about 33,764N. Thus, my mechanism was able to lift a maximum weight of 33.764N to the maximum height of 0.5m.