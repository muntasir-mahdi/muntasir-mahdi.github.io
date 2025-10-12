---
layout: page
title: Python Automation for PPMS–VNA and Transport Measurements
description: Python-based automation for synchronized magnetic field and frequency sweeps using PPMS, Agilent PNA 5227A, and Keithley instruments.
img: assets/img/projects/ppms_vna_bg.jpg
importance: 2
category: Graduate Research
---

### ⚙️ Project Overview

Developed a **Python-based automation suite** for synchronized magnetic-field and frequency-dependent measurements, combining data acquisition from **Quantum Design PPMS**, **Agilent PNA 5227A**, and **Keithley 6221/2182A** instruments.  
The software automates **FMR (Ferromagnetic Resonance)**, **Electrical Transport Option (ETO)**, and **frequency-vs-field S<sub>21</sub>** measurements — replacing expensive commercial packages and saving over **$4,000 in software costs**.

---

### 🧠 Motivation

Commercial PPMS–VNA integration tools are limited and often lack flexibility for advanced magneto-transport studies.  
This project aimed to build an **open, modular alternative** that allows:
- Automated frequency and magnetic field sweeps
- Real-time acquisition, averaging, and data saving
- Inter-instrument synchronization with precise timing
- Live plotting and post-measurement data parsing

---

### 🧩 Technical Implementation

- **Language:** Python (v3.11)  
- **Communication Protocols:**  
  - GPIB and VISA (via `pyvisa`)  
  - Quantum Design API for PPMS control  
- **Supported Instruments:**  
  - Agilent PNA 5227A (S<sub>21</sub> scattering measurements)  
  - Keithley 6221 (current source) and 2182A (nanovoltmeter)  
  - PPMS DynaCool (field, temperature, and ETO integration)  
- **Core Libraries:** `numpy`, `matplotlib`, `pandas`, `pyvisa`, `qcodes`, `scipy`  
- **Features:**  
  - Frequency sweep automation with synchronized field ramping  
  - Temperature-stabilized measurement loops  
  - Multi-scan averaging and noise filtering  
  - CSV + JSON output for post-processing and plotting  
  - Modular GUI-free design for remote execution  

---

<div class="row justify-content-sm-center">
  <div class="col-sm-6 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/projects/freq_field_sweep.jpg" title="Automated frequency vs field (S21) sweep using Python" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm-6 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/projects/transport_ppms.jpg" title="Electrical transport measurement using PPMS–Keithley setup" class="img-fluid rounded z-depth-1" %}
  </div>
</div>

<div class="caption">
  (Left) Automated S<sub>21</sub> frequency-field mapping via PPMS–VNA interface.  
  (Right) ETO resistivity and Hall measurement system integrated via Python.
</div>

---

### 🧪 Applications

- **Ferromagnetic Resonance (FMR):**  
  Automated frequency–field mapping to extract resonance fields, linewidths, and effective damping.

- **Electrical Transport Option (ETO):**  
  Temperature- and field-dependent resistance, Hall, and magnetoresistance data collection.

- **Hybrid FMR–Transport Studies:**  
  Combined measurements for studying magneto-electric coupling in heterostructures.

---

### 💻 Code Access

Full source code and example datasets are available on GitHub:

- 🧩 [PPMS–VNA Automation](https://github.com/yourusername/ppms-vna-automation)  
- 🔌 [PPMS–Keithley Transport Automation](https://github.com/yourusername/ppms-keithley-transport)

> Both repositories include instrument command templates, VISA initialization examples, and sample measurement logs for direct use in PPMS labs.

---