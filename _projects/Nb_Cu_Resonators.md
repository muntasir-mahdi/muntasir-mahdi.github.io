---
layout: page
title: Superconducting Nb & Cu Resonator/CPW Fabrication
description: Microfabrication of superconducting Nb resonators/ CPWs for cryogenic measurements and Cu resonators/ CPWs for room-temperature testing.
img: assets/img/nb_cu_cpw_res/Top_3D.jpg
importance: 2
category: Graduate Research
---

## Overview

For multiple projects I have done the **fabrication and characterization** of:

- **Nb resonators and CPWs** for low-temperature, cryogenic experiments
- **Cu resonators and CPWs** for room-temperature S-parameter testing

The key components of this work:

- Electroplating **Indium (In) bump structures** on resonator & coplanar waveguide (CPW) chips for **spin pumping and magnetic control interfaces**. Details in <a href="{{ '/projects/electroplating/' | relative_url }}"><strong>Electroplating</strong></a>.
- DC lines enabled **current-controlled magnon–magnon and magnon–photon coupling** in hybrid quantum systems.
- Established a **repeatable fabrication workflow** and validate resonator performance across **temperatures and magnetic fields**.

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
- **Deposition:** DC sputtering of Nb (200 nm), and Cu (150 nm)
- **Patterning:** UV lithography, lift-off for Cu and Nb
- **Geometry:** Quarter-wave CPW resonators (50 Ω feedline, λ/4 open stub)
- **Indium Bumps:** Electroplated onto patterned trenches to create **low-resistance current injection contacts** for tunable coupling experiments
- **Packaging:** Wire-bonded to custom PCBs for VNA measurements

## Measurements

**Room-Temperature (Cu):** S-parameter and impedance characterization using a **VNA**.

**Low-Temperature (Nb):** Cryogenic measurements of S<sub>21</sub> and Q-factor at 1.7 K, demonstrating high-quality resonator performance and compatibility with hybrid magnonic architectures.

<div class="row justify-content-center">
  <div class="col-md-12 mt-3 mt-md-0">
    {% include figure.liquid 
        loading="eager" 
        path="assets/img/nb_cu_cpw_res/nb_s21.jpg" 
        title="Nb resonator S21 measurement (a) and corresponding Q-factors (b)" 
        class="img-fluid rounded shadow-lg" 
    %}
  </div>
</div>
<div class="caption text-center small text-muted mt-2">
  Nb resonator performing under magnetic fields measured at 1.7 K: S21 measurements (a) and corresponding Q-factors (b)
</div>

---

## Electroplating Indium (for CPW chips)

<div class="container mt-4">
  <div class="row justify-content-center">
    <div class="col-md-5 col-sm-6 text-center mb-4">
      {% include figure.liquid path="assets/img/nb_cu_cpw_res/cpw_layout.jpg" title="CPW bump pattern" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-md-6 col-sm-6 text-center mb-4">
      {% include figure.liquid path="assets/img/nb_cu_cpw_res/bump_pattern.PNG" title="After electroplating" class="img-fluid rounded z-depth-1" %}
    </div>
  </div>

  <div class="row justify-content-center">
    <div class="col-md-5 col-sm-6 text-center mb-4">
      {% include figure.liquid path="assets/img/nb_cu_cpw_res/Top_3D.jpg" title="3D bump profile" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-md-6 col-sm-6 text-center mb-4">
      {% include figure.liquid path="assets/img/nb_cu_cpw_res/after_plating.PNG" title="CPW layout" class="img-fluid rounded z-depth-1" %}
    </div>
  </div>

  <div class="caption text-center text-muted small mt-2">
    For CPW wafers: (a) CPW layout used for current-controlled magnon coupling, (b) Profilometry of In bump pattern trenches, , 
    (c) 3D view of indium bumps, and (d) Electroplated bumps after resist stripping.
  </div>
</div>

---

## Key Outcomes

- Established a **reproducible fabrication workflow** for Nb and Cu resonators/CPWs
- Developed **indium bump integration** for current-driven magnon–magnon and magnon–photon coupling
- Verified **resonator performance trends** across magnetic fields
- Provided a **baseline for cryogenic hybrid quantum experiments**
- Integrated **Microwave Simulation → Mask/ PCB Design → fabrication → measurement pipeline**

---

## Tools & Methods

<p align="center">
   <img src="https://media.imgcdn.org/repo/2023/03/keysight-advanced-design-system/Keysight-Advanced-Design-System-ADS-Free-Download.jpg" alt="ADS" height="110" style="margin-right:10px;">
</p>

- **Software:** Keysight ADS, KLayout, Python
- **Equipment:** DC sputter system, mask aligner, VNA, optical profiler, electroplating setup
- **Collaboration:** Supervised by [Dr. Michael Hamilton](https://fast.auburn.edu/), conducted at [Alabama Micro/Nano Science and Technology Center](https://www.eng.auburn.edu/amstc/)

---
