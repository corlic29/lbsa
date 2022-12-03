---
title: Camera
layout: default
parent: Control
nav_order: 2
---
## [](#header-2)Camera

This component is responsible for the app-camera connection. This is initiated simultaneously with the start of an app. The component first determines if the Image Acquisition Toolbox is present in the used version of the MATLAB software.
Together with that, the app runs through each of the available add-on camera adapter, that enables connection with the camera. Such an add-on has to be installed separately according to the camera manufacturer's documentation, regarding camera operation through MATLAB.

![](./assets/images/Initation.png)

The step-by-step notifications of this process are displayed in the command line:

![](./assets/images/Command_line.png)

After the initiation, the user will be able to select one of the active camera adapters:

![](./assets/images/Initation_2.png)

Which successfully opens the app preview. In the last process, the user has to select the proper camera resolution in the camera selection toolbar:

![](./assets/images/Camera_selection.png)

This opens the new window with the live camera preview.

----
