---
layout: page
title: NbN Superconducting Resonator for Strong Magnon–Photon Coupling
description: Fabrication and measurement of NbN superconducting resonators demonstrating strong coupling with YIG spheres.
img: assets/img/NbN/nbn_s21.jpg
importance: 1
category: Graduate Research
giscus_comments: false
---

Superconducting resonators enable strong interactions between microwave photons and magnons, forming a key platform for hybrid quantum systems. This project demonstrates:
- **NbN microstrip resonators** integrated with **yttrium iron garnet (YIG)** spheres to realize **strong magnon–photon coupling** at cryogenic temperatures. 
- The DC lines and Indium bumps were aimed for current-controlled magnon–photon coupling.
- Details of the electroplating are described on <a href="/projects/Nb_Cu_Resonators/">CPW Fabrication</a> and <a href="/projects/electroplating/">Electroplating Indium</a>.

---

### Design and Fabrication

1. I designed **meander-type microstrip NbN resonators** (10 mm × 5 mm) optimized for magnetic-field-dependent coupling experiments. 
2. I have fabricated the devices on **intrinsic Si substrates** (525 µm thick) with **250 nm NbN** traces deposited by **DC reactive sputtering**. 
3. **Al contact pads** were added for microwave wirebonding, and a **NbN backside ground plane** completed the structure.

<div class="row">
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/NbN/nbn_mask.jpg" title="NbN resonator mask design" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/NbN/nbn_wafer.jpg" title="Fabricated NbN chip on sapphire" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/NbN/nbn_pcb.jpg" title="YIG sphere mounted on resonator center line" class="img-fluid rounded z-depth-1" %}
  </div>
</div>

<div class="caption">
  Left: NbN Resonator layout. Middle: Fabricated resonators on DSP Si wafers. Right: YIG sphere positioned for coupling measurement.
</div>

---

### Measurement and Characterization

- The assembly was tested in a **Quantum Design PPMS** for cryogenic and magnetic-field measurements. 
- A **VNA (Agilent N5227A)** was used to perform **S-parameter measurements** (S₁₁, S₂₁) from 100 MHz – 30 GHz at 1.8 K. 
- An in-plane and out-of-plane magnetic field was applied to drive the YIG into **ferromagnetic resonance (FMR)** and observe magnon–photon hybridization.

<div class="mt-3 mt-md-0 text-center">
  {% include figure.liquid 
      path="assets/img/NbN/nbn_s21.jpg" 
      title="S-parameters of a resontor with and without the YIG sphere" 
      class="img-fluid rounded z-depth-1" 
  %}
</div>

<div class="mt-4 mt-md-2 text-center">
  {% include figure.liquid 
      path="assets/img/NbN/nbn_s21_Q.jpg" 
      title="Corresponding Q-factors of a resontor with and without the YIG sphere" 
      class="img-fluid rounded z-depth-1" 
  %}
</div>

<div class="caption text-center small text-muted mt-2">
  Top: S-parameters of a resontor with and without the YIG sphere<br>
  Bottom: Corresponding Q-factors of a resontor with and without the YIG sphere.
  <br> Reprinted with permission from M. Mahdi et al., <em>IEEE Trans. Appl. Supercond.</em>, vol. 35, no. 5, Aug 2025. © IEEE.
</div>   
---

### Key Results

- At 1.8 K, the system exhibited **clear avoided crossing** in the S₂₁ spectra, confirming **strong coupling** between microwave photons and magnons.
- These results establish a scalable pathway toward **hybrid quantum magnonic devices** based on superconducting circuits.

> _“Hybrid systems like NbN–YIG platforms bridge the gap between superconducting quantum circuits and magnonic information carriers.”_

---

### Acknowledgment

This research is supported by the **Air Force Office of Scientific Research (AFOSR)** under grant funding for hybrid quantum systems.

<div class="text-center mt-3">
  <img src="https://bioannualreport2022.engr.ucr.edu/media/1136/download?attachment" alt="AFOSR logo" class="img-fluid" style="max-width:180px;">
</div>
