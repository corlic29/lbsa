---
title: Gerchberg-Saxton Correction
layout: default
parent: Beam shaping
nav_order: 3
has_children: true
---

In this section, the process of correcting the optical setup with the built-in Gerchberg-Saxton iterative algorithm and the optical vortex image will be introduced. The panel responsible for adjusting algorithm parameters is presented below:

![](/lbsa/assets/images/GS_empty.png)
 

However, the user will have to use the `optical vortex`, `blazed grating` and `aperture` to find the proper algorithm parameters. 

The procedure:
##### [](#header-5)The procedure:

1.  Use the `optical vortex`, `blazed grating`, and `aperture` to align the optical setup so that the uncorrected vortex will be visible in 1st order of diffraction at the Fourier plane. The circular aperture is crucial for the algorithm to deliver correct results. In most cases, the distorted vortex of topological charge m=1 should resemble the one below (image of the vortex at Fourier plane, magnified by a 20x objective):

![](/lbsa/assets/images/Uncorrected.png)

2.  Click the `1st grating button` in the G-S panel in order to upload selected diffraction grating parameters. 
3.  Choose the slightly different `blazed grating` parameters that will produce a similar image slightly shifted. Click the `2nd grating button` and upload the 2nd grating parameters.
4.  Choose `Axes` (x or y), to determine which of the `blazed grating` parameter was modified. For the best performance, we suggest not using the diagonal grating, therefore we limit possible options to either x or y grating shift. If diagonal grating is required, one can adjust the no. of grooves of the other component so that it’ll remain stable when switching from the 1st to 2nd grating. The exemplary case is presented below:
![](/lbsa/assets/images/GS_grating.png)

