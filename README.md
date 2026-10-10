# Antenna Resonant Frequency & SWR Calculator

Ham radio antenna calculator with three modes: half-wave dipole resonant frequency, quarter-wave vertical physical length, and SWR analysis with reflection coefficient and return loss.

## Key Features

- Mode A (Half-wave Dipole): input physical length and velocity factor, compute resonant frequency (f = 150·vf / L MHz) and identify the ham band
- Mode B (Quarter-wave Vertical): input target frequency, compute physical length (L = 71.25 / f m) in both metres and feet
- Both antenna modes produce a ±20% sweep table showing how frequency or length changes across the variation range
- SWR Calculator: enter feed-line impedance (default 50 Ω) and antenna impedance to get SWR ratio, reflection coefficient, power reflected %, return loss (dB), and a colour-coded rating (Excellent/Good/Acceptable/Poor)
- Visual SWR meter bar and automatic ham-band identification against 14 standard bands from 160m to 23cm
