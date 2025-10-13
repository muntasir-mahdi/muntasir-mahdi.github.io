---
layout: page
title: RFID-Based Security and Access Tracking System
description: Development of an RFID-based digital access control and monitoring system for institutional security.
img: assets/img/projects/rfid_access_bg.jpg
importance: 3
category:
---

This project focused on developing an **RFID-enabled security and access tracking system** to improve laboratory and building safety within the university environment.  
It was funded by the **Shahjalal University Research Center (SUSTRC)** during **2016–2017**.

---

### 🔐 Overview

The system was designed to **authenticate user entry through RFID tags** and automatically **log access data to an online database**.  
This provided real-time visibility into personnel movement, enhancing accountability and facility security.

My key contributions included:

- **Circuit and PCB design** for RFID tag reader integration
- **Firmware development** for microcontroller-based access verification
- **Database and network interface setup** for remote data logging
- **Testing and calibration** for reliability under varied use conditions

<div class="row">
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/projects/rfid_reader_module.jpg" title="Custom RFID reader and controller PCB" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/projects/rfid_lab_access.jpg" title="System installed for lab entry access" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/projects/rfid_data_logging.jpg" title="Online data logging dashboard" class="img-fluid rounded z-depth-1" %}
  </div>
</div>

<div class="caption">
  Left: RFID reader PCB. Middle: Access point setup. Right: Data logging interface.
</div>

---

### ⚙️ Technical Features

- RFID-based **ID authentication** using unique tag serials
- **Microcontroller-driven control** (Atmega328p) with serial-to-Ethernet communication
- **Online MySQL database** for access time and user tracking
- Modular architecture allowing **expansion to multiple access points**

---

### 🧩 Funding & Acknowledgment

This project was funded by the  
**Shahjalal University of Science & Technology Research Center (SUSTRC)**, Sylhet, Bangladesh.

---

> _“Bridging physical access and digital monitoring to make campus environments smarter and more secure.”_
