---
title: Control
layout: default
has_children: true
nav_order: 2
---

This section of the LBSA is responsible for the communication with external devices. The LBSA requires the MATLAB R2020a or newer, with the Image Acqusition Toolbox. Additionally, user is responsible to install adaptors enabling software - camera communication, through add-ons avaialble within MATLAB. At the initation phase, the LBSA will check available components and display their status in the commend line.

![](/lbsa/assets/images/Command_line.png)

In the brought example, four of such adaptors were installed: winvideo, gentl, gige and pointgrey. Two among them detected cameras connected to the computer, therefore they were mentioned as a _Detected cameras_. Additionally, LBSA detected one SLM having the 1920 x 1080 resolution.

The LBSA control section consists of three components. The upper component interconnects Spatial Light Modulator, Camera and the local hard drive. In particular, user has the possibility to choose the camera preview and determine if the SLM is properly connected. The middle section provides the preview of the designed hologram. In case the SLM is connected, this serves also as a preview of what is currently being displayed on the SLM. Finally, the bottom section indicates which among LBSA component is active aand taken into account when calculating the final hologram. This is indicated by the green diode status next to the name of the particular function. 

![](/lbsa/assets/images/Control_full.png)



----
