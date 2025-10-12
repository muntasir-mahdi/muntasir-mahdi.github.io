---
layout: page
title: Superconducting Nb/Cu Resonator Fabrication & Measurement
description: Design, fabrication, and room-temperature measurement of superconducting Nb and Cu microwave resonators.
img: assets/img/6.jpg
importance: 4
category: Graduate Research
---

## Overview

This project focused on the **design, microfabrication, and characterization** of superconducting **niobium (Nb)** and **copper (Cu)** resonators, fabricated on Si and sapphire substrates.  
Although these devices are typically operated at cryogenic temperatures, our goal was to explore **room-temperature fabrication consistency, impedance characteristics, and parasitic loss trends** as a foundation for low-temperature quantum measurements.

<div class="row justify-content-sm-center">
  <div class="col-sm-6 mt-3 mt-md-0">
    {% include figure.liquid loading="eager" path="assets/img/projects/nb_pattern.jpg" title="Patterned Nb resonator under microscope" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm-6 mt-3 mt-md-0">
    {% include figure.liquid loading="eager" path="assets/img/projects/cu_device.jpg" title="Copper resonator sample after lift-off" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
<div class="caption">
  Left: Lithographically defined Nb coplanar waveguide resonator (CPW).  
  Right: Cu resonator fabricated for room-temperature impedance characterization.
</div>

---

## Fabrication Process

The devices were fabricated using **optical lithography and thin-film deposition** at the Auburn University cleanroom:

- **Substrate:** High-resistivity Si and sapphire wafers  
- **Deposition:** DC sputtering of Nb (200 nm) and Cu (150 nm) layers  
- **Patterning:** UV lithography followed by wet etching for Nb and lift-off for Cu  
- **Geometry:** Quarter-wave CPW resonator (50 Ω matched feedline with λ/4 open stub)  
- **Packaging:** Wire-bonded to a custom-designed PCB for high-frequency measurements

<div class="row">
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/projects/mask_design.jpg" title="Mask layout in KLayout" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/projects/sputter.jpg" title="DC sputtering system used for Nb/Cu deposition" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/projects/pcb_mount.jpg" title="PCB packaging and SMA interface" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
<div class="caption">
  (a) KLayout mask design; (b) DC sputtering chamber used for Nb/Cu deposition;  
  (c) Packaged resonator ready for VNA measurements.
</div>

---

## Room-Temperature Measurement

Measurements were performed using a **Keysight Vector Network Analyzer (VNA)** to evaluate:

- **S<sub>21</sub> transmission response**
- **Q-factor degradation at RT**
- **Frequency shift due to fabrication tolerances**
- **Parasitic coupling and impedance mismatch effects**

<div class="row justify-content-sm-center">
  <div class="col-sm-8 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/projects/vna_data.jpg" title="VNA transmission measurement" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
<div class="caption">
  Measured S<sub>21</sub> transmission spectrum of the Nb resonator at room temperature, showing resonant dip and insertion loss characteristics.
</div>

---

## Key Outcomes

- Verified **fabrication process repeatability** for Nb and Cu thin films  
- Identified dominant **loss mechanisms** at RT (surface roughness and contact resistance)  
- Established a baseline for **cryogenic follow-up characterization**  
- Developed complete **CAD-to-measurement pipeline** (KLayout → cleanroom → VNA)

---

## Tools & Methods

- **Software:** KLayout, MATLAB, and Python for post-processing  
- **Equipment:** DC sputter system, mask aligner, VNA, optical profiler  
- **Collaboration:** Supervised by [Prof. Tony T. Tang](https://eng.auburn.edu/directory/tzt0024) and conducted at the [Auburn Nanofabrication Facility](https://eng.auburn.edu/research/facilities.html)

---

## Gallery

<div class="row">
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/projects/nb_chip.jpg" title="Completed Nb resonator chip" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/projects/probe_setup.jpg" title="RF probe station setup" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
<div class="caption">
  Completed Nb resonator chip and RF probe measurement setup.
</div>

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
