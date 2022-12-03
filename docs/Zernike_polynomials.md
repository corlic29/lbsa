---
title: Zernike
layout: default
parent: Beam shaping
nav_order: 4

---
## [](#header-2)Zernike

In order to manually introduce or subtract aberration, the Zernike polynomial component has been added as a separate function. 
It allows the user to introduce Zernike polynomials, by specifying the value of polynomials having an azimuthal and radial index, 
according to:

![](/lbsa/assets/images/Zernike_definition.png)

Which is mirrored in the LBSA:

![](/lbsa/assets/images/Zernike_panel.png)

Each polynomial is calculated on the unitary disk, where the shorter side of the set resolution is taken as the disk diameter. 
By default, the function is restricted to 3rd-order Zernike polynomials, however,
 more complex holograms can be easily achieved by the combination of those available.
As the result, the set of polynomials will be combined into the final hologram and superposed with other LBSA functions, in the control panel.  

The exemplary phase map, representing Vertical astigmatism is presented below:

![](/lbsa/assets/images/Vertical_astgm.bmp)

