# MOSFET Analog Amplifier Stages

This repository contains implementations and notes on commonly used MOSFET small-signal amplifier stages.  
Each folder corresponds to one topology, including its schematic, operating principle, and key equations.

MOSFET amplifiers are widely used because of their high input impedance, low power consumption, and ease of integration in ICs. Different configurations trade off gain, linearity, bandwidth, and impedance to suit different applications such as voltage amplification, buffering, and RF front-ends.

---

## 📁 Amplifier Topologies

### 1. Common-Source Amplifier with Resistive Load
**Folder:** [`common_source_resistive_load`](./CS amplifier with Resistive load)

A basic voltage amplifier using a drain resistor as the load. It provides moderate gain with 180° phase inversion.


---

### 2. Common-Source with Diode-Connected Load
**Folder:** [`common_source_diode_load`](./common_source_diode_load)


---

### 3. Common-Source with Current-Source (Active) Load
**Folder:** [`common_source_active_load`](./common_source_active_load)


---

### 4. Common-Source with Triode-Region Load (Voltage-Controlled Resistor)
**Folder:** [`common_source_triode_load`](./common_source_triode_load)


---

### 5. Common-Source with Source Degeneration
**Folder:** [`common_source_source_degeneration`](./common_source_source_degeneration)

---

### 6. Source Follower (Common-Drain)
**Folder:** [`source_follower`](./source_follower)



---

### 7. Common-Gate Amplifier
**Folder:** [`common_gate`](./common_gate)


---


