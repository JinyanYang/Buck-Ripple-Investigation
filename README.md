# Buck Converter Ripple Voltage Investigation

This repository presents an experimental study of **output ripple voltage** in a **buck (step-down) converter**, focusing on the impact of capacitor **ESR** and capacitance on ripple and stability.  
The work was originally a lab assignment and has been adapted into a public, educational-style portfolio project.

---

## Repository Structure

```
buck-ripple-investigation/
├── README.md
├── LICENSE
├── .gitignore
├── report/
│   └── RippleVoltage_Report.pdf   # Anonymized version of the original report
├── models/                        # Circuit/Simulink screenshots (add here)
├── figures/                       # Waveforms and comparison plots (add here)
└── scripts/                       # MATLAB/LTSpice scripts (optional)
```

---

## Project Overview

- **Objective**: Quantify how **capacitor ESR** and **capacitance** affect the buck converter's output ripple and stability.  
- **Method**: Build/simulate the buck converter; sweep ESR (e.g., 3.1 mΩ → 0.5 mΩ) and capacitance; record waveforms: Vout ripple, inductor current, diode/switch current.  
- **Tools**: MATLAB/Simulink, LTSpice (or equivalent).

---

## Key Findings (from the report)

- Larger **ESR** → **higher ripple** and reduced voltage stability.  
- Increasing **capacitance** → **lower ripple** and improved stability.  
- Inductor current ripple correlates with output ripple and switching frequency.

*(Insert your actual plots in `figures/` and reference them here.)*

---

## Suggested Figures in report

- Buck converter circuit diagram (`models/buck_circuit.png`)  
- Output ripple comparison for different ESR values (`figures/ripple_comparison.png`)  
- Inductor current waveform (`figures/inductor_current.png`)  

---

## How to Reproduce

1. Open the report `report/RippleVoltage_Report.pdf` for the full methodology and results.  
2. Recreate the circuit in your simulator (LTSpice/Simulink).  
3. Sweep ESR/capacitance and capture Vout/IL waveforms.  
4. Export images to `figures/` and update this README with links.

---

## Notes

- Personal identifiers (student ID / declaration) should be removed before making the repo public.  
- This repository is for **educational/portfolio** use and is not intended as a product design reference.

---

## Author

Jinyan Yang — MSc in Renewable Energy Systems
