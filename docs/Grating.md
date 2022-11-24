---
title: Blazed and sinusoidal grating
layout: default
parent: Phase shaping & transformation
grand_parent: Beam shaping
nav_order: 3

---
## [](#header-2)Blazed and sinusoidal grating

This subsection consists of two functions: 'blazed' and 'sinusoidal' phase grating. 
The subsection allows choosing between these two since they cannot exist together by default. 
However, if the user would like to superpose them on purpose, it is suggested to save one as an 'external hologram', 
load it into the app and superpose it with the other grating.

![](/lbsa/assets/images/Blazed_and_sinusoidal_grating.png)

In case any of the gratings is selected, the other vanishes and cannot be chosen. 
It will be enabled again only if the first grating will be turned off.

![](/lbsa/assets/images/Blazed_and_sinusoidal_grating_2.png)

Users may define a number of grooves in both the x and y direction (nx, ny, respectively). 
No. of groves should be a positive integer. Additionally, information about the grating vector [1/px] 
for each grating is provided to let the user control the spatial frequency of the designed grating. 
However, the spatial frequency is calculated with respect to hologram dimensions, 
therefore identical no. of grooves does not indicate the identical spatial frequency. 
Two examples of gratings are presented below. Blazed (nx=5, ny=5, on the left) and Sinusoidal (nx=5, ny=0, on the right). 

![](/lbsa/assets/images/Gratings.png)

 


