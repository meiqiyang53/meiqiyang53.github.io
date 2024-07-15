---
layout: page
title: Spatially separated crystallization for selective lithium extraction from saline water
description: Design an efficient and self-concentrating crystallization method for the selective extraction of lithium from both brines and seawater via material engineering and surface treatment;
img: assets/img/background1.jpg
importance: 1
category: work
related_publications: true
---
Limited lithium supply is hindering the global transformation towards electrification and decarbonization. Current lithium mining can be energy, chemical and land intensive. Here we present an efficient and
self-concentrating crystallization method for the selective extraction of lithium from both brine and seawater. The sequential and separable crystallization of cation species with different concentrations and solubilities was enabled by a twisted and slender 3D porous natural cellulose fibre structure via capillary and evaporative flows. The process exhibited an evaporation rate as high as 9.8 kg m−2 h−1, and it selectively concentrated lithium by orders of magnitude. The composition and spatial distribution of crystals were characterized, and a transport model deciphered the ion re-distribution process in situ. We also demonstrated system scalability via a 100-crystallizer array.


    ---
    layout: page
    title: project
    description: a project with a background image
    img: /assets/img/background1.jpg
    ---

<div class="row">
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/a1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/a3.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
<!--     <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div> -->
</div>
<div class="caption">
     On the left, Schematic of the 3D spatial crystallization process. At the bottom position (Bottom), mixed Li and Na ions are carried upward via capillary flow. At the middle position (Middle), NaCl saturates and crystallizes, while Li species continue to move upward with the water flow. At the top position (Top), Li ions precipitate when the saline water completely evaporates. Middle, The Li/Na ratio increased along the 3D fibre crystallizer, with Li concentrated by >39 times at the top when using brine and >675 times at the top when using seawater. Right, Schematic of the geometry and parameters considered in the theoretical model. Prediction of the Li ion concentration as a function of the position inside the crystallizer and model prediction of the Li/Na ratio.
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/big1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Li is concentrated at the centre of the fibre crystallizer. a, Schematic showing that Li is concentrated inside the fibre crystallizer, surrounded by the Na-rich salt shell. b, SEM image of the cross-section. c, Na elemental map from the EDX, showing a circular shape surrounding the crystallizer structure. d, Li elemental map from the EDX, showing a dispensed distribution across the crystallizer’s cross-section. The Li elementary map was calculated by deducting the Na map from the Cl map. e, SEM image of the area between the fibres and salt crystals, pink-boxed in b. f, Na elemental map from the EDX, showing that only the salt crystals emitted clear Na spectra, while the fibre area showed no Na signal. g, Li elemental map from the EDX, showing that Li spectra were widely detected over the fibre areas, with the weakest signal at the bottom-right corner, where the NaCl crystals are located. h, Schematic showing that, in the centre Li-rich part, cubic NaCl crystals (blue) act as a core and LiCl form surrounding amorphous salt (pink). i, S/TEM image of the salt crystal sampled from the centre. j, TEM image of the blue-boxed area in i, showing a clear boundary between the two types of salt crystal. k, Layered EELS map confirmed two different elemental components aside the boundary. l–n, Cl (l), Na (m) and Li (n) elemental map from EELS. Cl covered the whole scope, and Na distributed only at the right side of the boundary, while Li distributed mostly at the left side.
</div>

You can also put regular text between your rows of images, even citations {% cite einstein1950meaning %}.
Say you wanted to write a bit about your project before you posted the rest of the images.
You describe how you toiled, sweated, _bled_ for your project, and then... you reveal its glory in the next row of images.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/a4.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    You can also have artistically styled 2/3 + 1/3 images, like these.
</div>

The code is simple.
Just wrap your images with `<div class="col-sm">` and place them inside `<div class="row">` (read more about the <a href="https://getbootstrap.com/docs/4.4/layout/grid/">Bootstrap Grid</a> system).
To make images responsive, add `img-fluid` class to each; for rounded corners and shadows use `rounded` and `z-depth-1` classes.
Here's the code for the last row of images above:

{% raw %}

```html
<div class="row justify-content-sm-center">
  <div class="col-sm-8 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm-4 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
```

{% endraw %}
