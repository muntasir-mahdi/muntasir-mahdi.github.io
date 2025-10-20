---
layout: page
title: Python Automation for PPMS–VNA and Transport Measurements
description: Python-based programming to automate measurements with synchronized magnetic field, temperature, and frequency sweeps using PPMS, Agilent PNA 5227A, and Keithley instruments.
img: assets/img/python/ppms_vna_bg.jpg
importance: 4
category: Graduate Research
---

### ⚙️ Project Overview & Motivation

I have developed a **Python automation suite** for synchronized magnetic-field, temperature and frequency-dependent measurements using:

- **Quantum Design PPMS**,
- **Agilent PNA 5227A**, and
- **Keithley 6221/2182A** instruments.

### 🧪 The software automates:

1. **FMR (Ferromagnetic Resonance)**: frequency–field mapping to extract resonance fields, linewidths, and effective damping.
2. **Electrical Transport Option (ETO)**: Temperature- and field-dependent Hall, and magnetoresistance data collection.
3. **Frequency-vs-field S<sub>21</sub>** measurements: microwave measurements by synchronizing with VNA

> It replaced an expensive commercial packages and saving over **$4,000**.

---

<div class="row justify-content-sm-center">
  <div class="col-sm-6 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/publication_preview/mahdi6-3532579-large.jpg" title="Automated frequency vs field (S21) sweep using Python" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm-6 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/python/MR_Python.jpg" title="Electrical transport measurement using PPMS–Keithley setup" class="img-fluid rounded z-depth-1" %}
  </div>
</div>

<div class="caption">
  (Left) Automated S<sub>21</sub> frequency-field mapping via PPMS–VNA interface.  
  (Right) ETO resistivity and Hall measurement system integrated via Python.
</div>
---

### 🧩 Technical Implementation

<p align="left">
   <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/c/c3/Python-logo-notext.svg/1200px-Python-logo-notext.svg.png" alt="Python" height="40" style="margin-right:10px;">
   <img src="https://media.licdn.com/dms/image/v2/D560BAQG5xabw5hAROA/company-logo_200_200/company-logo_200_200/0/1733947881555/quantum_design_logo?e=2147483647&v=beta&t=fzPqZwp6uHrnulOPZgjgDf2d6riW-IG9Z5Rvmc65bZY" alt="QD" height="40">
</p>

- **Language:** Python (v3.11)
- **Communication Protocols:**
  - GPIB and VISA (via `pyvisa`)
  - Quantum Design API for PPMS control
- **Supported Instruments:**
  - Agilent PNA 5227A (S<sub>11</sub>, S<sub>21</sub> scattering measurements)
  - Keithley 6221 (current source) and 2182A (nanovoltmeter)
  - PPMS DynaCool (field, temperature)
- **Core Libraries:** `numpy`, `matplotlib`, `pandas`, `pyvisa`, `scipy`
- **Features:**
  - Frequency sweep automation with synchronized field ramping
  - Temperature-stabilized measurement loops
  - Multi-scan averaging and noise filtering
  - CSV output for post-processing and plotting
  - Modular GUI-free design for remote execution

---

### 💻 Code Access

Full source code and example datasets are available on GitHub:

- 🧩 [PPMS–VNA Automation](https://github.com/muntasir-mahdi/PPMS-PyPNA.git)
- 🔌 [PPMS–Keithley Transport Automation](https://github.com/muntasir-mahdi/Keithley-PPMS-Integration.git)

> Repositories include ready-to-use command templates, VISA initialization scripts, and sample measurement logs for PPMS setups.

---
