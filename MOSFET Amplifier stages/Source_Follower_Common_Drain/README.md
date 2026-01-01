## NMOS Common-Source Amplifier with Source Degeneration

A voltage amplifier implemented using a drain resistor and a source degeneration resistor. The source degeneration introduces local negative feedback, resulting in moderate gain with 180° phase inversion, improved linearity, and reduced sensitivity to device parameter variations.

- **Gain:** \( A_v = -\dfrac{g_m R_D}{1 + g_m R_S} \)  
- Improved linearity and bias stability due to negative feedback  
- Lower gain compared to a basic common-source stage without degeneration  

This directory contains the design and LTspice simulation of an NMOS common-source amplifier with source degeneration. The implementation is limited to NMOS devices to keep the scope focused and practical.

[Open report (PDF)](CS_amplifier_with_source_degeneration.pdf)

