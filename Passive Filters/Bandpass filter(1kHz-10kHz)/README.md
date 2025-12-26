## RC Band-Pass Filter

Designed and simulated a band-pass filter by cascading a first-order RC high-pass stage with a first-order RC low-pass stage. The overall filter exhibits a second-order frequency response, allowing signals within a defined mid-frequency range to pass while attenuating both low-frequency and high-frequency components.

### Design Overview
- Implemented using passive RC components only (no inductors or active devices).
- High-pass section removes low-frequency components below the lower cutoff frequency.
- Low-pass section removes high-frequency components above the upper cutoff frequency.
- Cascading the two sections forms the band-pass response.

### Key Characteristics
- Filter type: Passive RC band-pass  
- Order: Second-order (two poles total)  
- Implementation: Cascaded first-order high-pass and low-pass sections  
- Application: Signal conditioning, noise reduction, and frequency selection

- [Open report (PDF)](band_pass_filter.pdf)
