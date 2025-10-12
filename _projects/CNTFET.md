---
layout: page
title: Characterization of Carbon Nanotube Field-Effect Transistor (CNTFET)
description: Analysis of CNTFET performance and parameter variation using MATLAB and NEGF simulations.
img: assets/img/cntfet_cover.jpg
importance: 1
category: Undergraduate Projects
related_publications: true
---

This project explored the **electrical characterization and modeling of carbon nanotube field-effect transistors (CNTFETs)**, focusing on how device parameters and doping profiles influence transport behavior.  
The analysis was carried out using **MATLAB** and **Simulink**, along with **nonequilibrium Green’s function (NEGF)**-based simulation frameworks.

---

### Simulation and Modeling

<div class="row">
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid loading="eager" path="assets/img/cntfet_model.jpg" title="CNTFET structure schematic" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid loading="eager" path="assets/img/iv_curve.jpg" title="Simulated I–V characteristics for varying doping profiles" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid loading="eager" path="assets/img/transfer_curve.jpg" title="Transfer characteristics from empirical CNTFET model" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
<div class="caption">
  Simulation results illustrating the effect of doping variation and channel length on I–V performance of CNTFETs. The NEGF framework enabled nanoscale transport analysis beyond drift-diffusion limits.
</div>

---

### Key Findings

- Developed and validated an **empirical CNTFET model** for performance analysis under varying device conditions.  
- Investigated **doping profile effects** on device output and transconductance.  
- Demonstrated strong agreement between **empirical models** and **quantum transport simulations**.  
- Showed that **non-uniform doping** significantly influences channel control and current modulation in nanoscale CNTFETs.

---

### Tools and Techniques

- **Simulation:** MATLAB, Simulink  
- **Theoretical Framework:** Nonequilibrium Green’s Function (NEGF)  
- **Device Parameters:** Channel diameter, gate oxide thickness, and doping concentration  
- **Outputs:** I–V characteristics, transconductance, subthreshold slope

---

### Related Publications

1. **Effect of doping profile variation on nanoscale cylindrical gate carbon nanotube field-effect transistor: a computational study using nonequilibrium Green’s function formalism**  
   *M. Mahdi, M. A. Hossain, S. Hussain, M. Hasan, H. U. Zaman, J. K. Saha*  
   *Semiconductor Science and Technology, 36(1), 015012 (2020)*  

2. **Performance analysis of an empirical model of carbon nanotube field-effect transistor**  
   *M. Mahdi, M. A. Hossain, J. K. Saha*  
   *2018 International Conference on Innovation in Engineering and Technology (ICIET), 2018*

---

<div class="row justify-content-sm-center">
  <div class="col-sm-8 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/cntfet_band.jpg" title="Band structure simulation of CNT channel under bias" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm-4 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/cntfet_doping.jpg" title="Spatial doping profile illustration" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
<div class="caption">
  Visualization of quantum transport simulation and spatial doping variation effects in CNTFET channels.
</div>

---

This study established a comprehensive computational framework for **nanoscale transistor modeling** and contributed to the understanding of **quantum transport phenomena** in carbon nanotube-based devices.
