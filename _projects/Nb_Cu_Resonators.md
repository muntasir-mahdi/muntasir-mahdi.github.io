---
layout: page
title: Superconducting Nb & Cu Resonator and CPW Fabrication
description: Microfabrication of superconducting Nb resonators/ CPWs for cryogenic measurements and Cu resonators/ CPWs for room-temperature testing.
img: assets/img/nb_cu_cpw_res/Top_3D.jpg
importance: 2
category: Graduate Research
---

## Overview

This project focused on the **fabrication and characterization** of:

- **Nb resonators and CPWs** for low-temperature, cryogenic experiments
- **Cu resonators and CPWs** for room-temperature impedance and S-parameter testing

A key component of this work involved developing **indium (In) bump structures** on coplanar waveguide (CPW) chips.  
These bumps serve as **spin pumping and magnetic control interfaces**, enabling **current-controlled magnon–magnon and magnon–photon coupling** in hybrid quantum systems. The overall goal was to establish a **repeatable fabrication workflow** and validate **resonator performance across temperatures**.

<div class="row justify-content-sm-center">
  <div class="col-sm-6 mt-3 mt-md-0">
    {% include figure.liquid loading="eager" path="assets/img/nb_cu_cpw_res/Nb_res.jpg" title="Nb resonator wafer for low-temperature measurement" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm-6 mt-3 mt-md-0">
    {% include figure.liquid loading="eager" path="assets/img/nb_cu_cpw_res/cu_res.jpg" title="Cu resonator wafer for room-temperature measurement" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
<div class="caption">
Left – Nb resonators for cryogenic testing; Right – Cu resonators for room-temperature characterization. Both have photoresist spun for dicing.
</div>

---

## Fabrication Process

Devices were fabricated using **optical lithography and thin-film deposition**:

- **Substrates:** High-resistivity double sided polished Si wafers
- **Deposition:** DC sputtering of Nb (200 nm) and Cu (150 nm)
- **Patterning:** UV lithography, lift-off for Cu and Nb
- **Geometry:** Quarter-wave CPW resonators (50 Ω feedline, λ/4 open stub)
- **Indium Bumps:** Electroplated onto patterned trenches to create **low-resistance current injection contacts** for tunable coupling experiments
- **Packaging:** Wire-bonded to custom PCBs for VNA measurements

<div class="row justify-content-sm-center">
  <div class="col-sm-8 mt-4 mt-md-0 text-center">
    {% include figure.liquid path="assets/img/nb_cu_cpw_res/bump_pattern.PNG" title="CPW bump pattern" class="img-fluid rounded z-depth-1" %}
  </div>
</div>

<div class="row justify-content-sm-center">
  <div class="col-sm-8 mt-4 mt-md-0 text-center">
    {% include figure.liquid path="assets/img/nb_cu_cpw_res/after_plating.PNG" title="Nb and Cu wafer spin-coated with resist before dicing" class="img-fluid rounded z-depth-1" %}
  </div>
</div>

<div class="row justify-content-sm-center">
  <div class="col-sm-8 mt-4 mt-md-0 text-center">
    {% include figure.liquid path="assets/img/nb_cu_cpw_res/Top_3D.jpg" title="3D bump profile" class="img-fluid rounded z-depth-1" %}
  </div>
</div>

<div class="caption">
For CPW wafers: (Top) Profilometry of In bump pattern trenches; (Middle) Electroplated bumps after photoresist stripping; (Bottom) 3D view of the indium bumps used for current-controlled magnon coupling.
</div>

---

## Measurements

**Room-Temperature (Cu):** S-parameter and impedance characterization using a **VNA**.

**Low-Temperature (Nb):** Cryogenic measurements of S<sub>21</sub> and Q-factor at 1.8 K, demonstrating high-quality resonator performance and compatibility with hybrid magnonic architectures.

<div class="row justify-content-sm-center">
  <div class="col-sm-8 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/nb_cu_cpw_res/nb_res_output.jpg" title="Nb resonator response at 1.8 K" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
<div class="caption">
Measured S<sub>21</sub> transmission for Nb (low-temperature) resonators, highlighting resonances below 10 GHz and confirming superconducting response at cryogenic temperatures.
</div>

---

## Key Outcomes

- Established a **reproducible fabrication workflow** for Nb and Cu resonators
- Developed **indium bump integration** for current-driven magnon–magnon and magnon–photon coupling
- Verified **resonator performance trends** across temperatures
- Provided a **baseline for cryogenic hybrid quantum experiments**
- Integrated **CAD → fabrication → measurement pipeline**

---

## Tools & Methods

- **Software:** Keysight ADS, KLayout, MATLAB, Python
- **Equipment:** DC sputter system, mask aligner, VNA, optical profiler, electroplating setup
- **Collaboration:** Supervised by [Dr. Michael Hamilton](https://fast.auburn.edu/), conducted at [Alabama Micro/Nano Science and Technology Center](https://www.eng.auburn.edu/amstc/)

---
