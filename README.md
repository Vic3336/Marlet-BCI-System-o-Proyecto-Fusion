# MARLET BCI SYSTEM (Project Fusion)

**Architect:** Víctor Manuel Ortega Smith  
**Version:** 2.0 (Stable)  
**Status:** Active Development / Integration Phase

## 🧠 Project Overview
The **Marlet BCI Architecture** is a high-performance signal processing bridge designed to interact with the **Emotiv Cortex API**. It functions as a fault-tolerant "Black Box" controller that translates raw EEG data into binary logic triggers for external hardware.

### Key Capabilities
* **Real-Time Filtering:** Advanced digital signal processing (DSP) using Butterworth and Notch filters.
* **Fault Tolerance:** Encapsulated execution blocks that prevent system crashes during external hardware failures.
* **Universal Integration:** Plug-and-play architecture for Robotics, IoT, and Drone control systems.

## 🛠 Integration Guide
This system listens on **Port 6868** (Cortex API). 

### Deployment
1.  Clone this repository.
2.  Install dependencies: `pip install -r requirements.txt`
3.  Execute the main controller: `python Marlet_Controller_v2.py`

---
**Copyright © 2026 Víctor Manuel Ortega Smith.** *All Rights Reserved.*
