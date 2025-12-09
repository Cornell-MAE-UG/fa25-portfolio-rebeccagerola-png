---
layout: project
title: MAE 3270 Torque Wrench Design
description: Just a spaceship that I designed
technologies: [Fusion, ANSYS Mechanical, Granta Material Database]
image: /assets/images/materialswrench.jpg
---

[Click here for my final write-up]({{ "/materialsfinal.pdf" | relative_url }})!

For this project, I designed a torque wrench by first performing hand calculations in MATLAB to size the critical cross-sections and ensure compliance with the required factors of safety for yield, fracture, and fatigue. These calculations established the baseline geometry, which I then modeled parametrically in Fusion for further refinement. I selected Aluminum 7075-T6 as the primary material due to its high specific strength and weight efficiency relative to steels commonly used in similar tools.

The finalized model was imported into ANSYS, where I conducted linear static, fracture, and fatigue analyses to validate the design. The simulation results confirmed that the maximum von Mises stress remained below allowable limits, the stress-intensity factors were well under the critical KIC for 7075-T6, and the predicted fatigue life exceeded the assignment’s minimum safety requirements. Overall, the workflow integrated analytical sizing, CAD-based optimization, and finite-element verification to produce a structurally sound torque-wrench design.


