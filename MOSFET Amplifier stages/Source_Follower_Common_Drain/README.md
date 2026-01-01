## NMOS Common-Source Amplifier with Source Degeneration

A voltage amplifier implemented using a drain resistor and a source degeneration resistor. The source degeneration introduces local negative feedback, resulting in moderate gain with 180° phase inversion, improved linearity, and reduced sensitivity to device parameter variations.

- **Gain:** \( Av = -gm RD/(1 + gm RS) \)  
- Improved linearity and bias stability due to negative feedback  
- Lower gain compared to a basic common-source stage without degeneration  

This directory contains the design and LTspice simulation of an NMOS common-source amplifier with source degeneration. The implementation is limited to NMOS devices to keep the scope focused and practical.

[Open report (PDF)](source_follower)

