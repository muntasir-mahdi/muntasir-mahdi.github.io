---
layout: page
title: Superconducting Nb & Cu Resonator and CPW Fabrication
description: Microfabrication of superconducting Nb resonators/ CPWs for cryogenic measurements and Cu resonators/ CPWs for room-temperature testing.
img: assets/img/nb_cu_cpw_res/6.jpg
importance: 4
category: Graduate Research
---

## Overview

This project focused on the **fabrication and characterization** of:

- **Nb resonators and CPWs** for low-temperature, cryogenic experiments  
- **Cu resonators and CPWs** for room-temperature impedance and S-parameter testing  

The goal was to establish a **repeatable fabrication workflow** and validate **resonator performance across temperatures**.

<div class="row justify-content-sm-center">
  <div class="col-sm-6 mt-3 mt-md-0">
    {% include figure.liquid loading="eager" path="assets/img/nb_cu_cpw_res/Nb_res.jpg" title="Nb resonator wafer for low-temperature measurement" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm-6 mt-3 mt-md-0">
    {% include figure.liquid loading="eager" path="assets/img/nb_cu_cpw_res/cu_res.jpg" title="Cu resonator wafer for room-temperature measurement" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
<div class="caption">
Left – Nb resonators for cryogenic testing; Right – Cu resonators for room-temperature characterization. Both has photoresist spun for dicing.
</div>

---

## Fabrication Process

Devices were fabricated using **optical lithography and thin-film deposition**:

- **Substrates:** High-resistivity Si and sapphire wafers  
- **Deposition:** DC sputtering of Nb (200 nm) and Cu (150 nm)  
- **Patterning:** UV lithography, lift-off for Cu and Nb  
- **Geometry:** Quarter-wave CPW resonators (50 Ω feedline, λ/4 open stub)  
- **Packaging:** Wire-bonded to custom PCBs for VNA measurements  

<div class="row">
  <div class="col-sm mt-5 mt-md-0">
    {% include figure.liquid path="assets/img/nb_cu_cpw_res/bump_pattern.PNG" title="CPW bump pattern" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm mt-5 mt-md-0">
    {% include figure.liquid path="assets/img/nb_cu_cpw_res/after_plating.PNG" title="Nb and Cu wafer spin-coated with resist before dicing" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm mt-5 mt-md-0">
    {% include figure.liquid path="assets/img/nb_cu_cpw_res/Top_3D.jpg" title="3d_bump" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
<div class="caption">
For CPW wafers: (a) Profilometry of In bump pattern trenches; (b) Bump profile after electroplating and photoresist stripped; (c) 3D view of the electroplated indium bumps
</div>

---

## Measurements

**Room-Temperature (Cu):** S-parameter and impedance characterization using a **VNA**.  

**Low-Temperature (Nb):** Cryogenic measurements of S<sub>21</sub> and Q-factor at 1.8 K, demonstrating high-quality resonator performance.

<div class="row justify-content-sm-center">
  <div class="col-sm-8 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/nb_cu_cpw_res/nb_res_output.jpg" title="Nb resonator response at 1.8 K" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
<div class="caption">
Measured S<sub>21</sub> transmission for Nb (low-temperature) resonators, highlighting resonances below 10 GHz.
</div>

---

## Key Outcomes

- Established a **reproducible fabrication workflow** for Nb and Cu resonators  
- Verified **resonator performance trends** across temperatures  
- Provided a **baseline for cryogenic quantum experiments**  
- Integrated **CAD → fabrication → measurement pipeline**

---

## Tools & Methods

- **Software:** KLayout, MATLAB, Python  
- **Equipment:** DC sputter system, mask aligner, VNA, optical profiler  
- **Collaboration:** Supervised by [Dr. Michael Hamilton](https://fast.auburn.edu/), conducted at [Alabama Micro/Nano Science and Technology Center](https://www.eng.auburn.edu/amstc/)

---