---
title: Transformation
layout: default
parent: Phase shaping & transformation
grand_parent: Beam shaping
nav_order: 6

---
## [](#header-2)Transformation


![](/lbsa/assets/images/Translation.png)


This function allows the user to translate or rotate the final hologram. 
First of all, the user selects shift in both x and y direction (`Translation x` and `Translation y` respectively). 
Additionally, rotation of the final hologram is possible, with one restriction, 
the image will be cut to match the SLM resolution. The example below presents the shifted hologram, 
of the optical vortex with a fresnel lens, covered by an aperture. 
Such a hologram has been shifted by 200px in the y direction and 30px in the x direction.

![](/lbsa/assets/images/Translated_all_200_30.bmp)


An optional feature `vortex only switch` enables vortex-only shift, 
which treats the vortex phase map as a separate map, that will be translated or rotated. 
This becomes crucial when the vortex has to be shifted independently inside the beam. 
By default, this option is set to off, which treats all superposed phase maps as a single unit. 
If turned on, it picks the vortex phase map, translates, and rotates this map only, which is later superposed with other phase maps. 
The example below presents the analogical hologram as previously, this time with the vortex-only feature enabled.

![](/lbsa/assets/images/Translated_vortex_200_30.bmp)
 


