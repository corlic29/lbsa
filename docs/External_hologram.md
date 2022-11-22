---
title: External hologram
layout: default
parent: Beam shaping
nav_order: 1
---

The “External hologram” is the first tab available in the Design section. 
The role of the features existing under this tab is to provide a way to import external holograms, 
represented as a grayscale image. This becomes useful in case the app has to implement any hologram created previously, 
this can be a hologram prepared within the app or be completely external, representing for instance the SLM surface, 
provided by the manufacturer.

![](./assets/images/External.png)
 

The `Load hologram` button loads a hologram from the external file, saved as an image graphic file. 
The app works with .jpg .bmp .png formats, allowing multiple holograms to be selected. 
However, each hologram has to be designed as a grayscale image. 
Properly loaded holograms should be displayed in the hologram list box. The box can be cleared through the `Clear` button. 


The loaded hologram list contains all of the loaded holograms. 
The hologram is enabled by double-clicking. This will display the chosen hologram in the external hologram axes beneath. 
The “Add to SLM” checkbox determines if the hologram will be taken into account when calculating the final hologram displayed on the SLM.
