# 🌀 Nested Harmonic Cocoon: Bio-Resonance Architecture

> A suite of web-based CAD tools for mathematically modelling, simulating, and constructing a clinical-grade **photobiomodulation and scalar-wave acoustic therapy bed**.

---

## Overview

The Nested Harmonic Cocoon engineering system is built at the intersection of three physical phenomena:

| Phenomenon | Mechanism | Effect |
|---|---|---|
| **Asymmetrical Scalar Magnetics** | Stacked Series Bifilar coils | 4:1 expanding zero-point field |
| **Optical Collimation** | Stroboscopic (16.5 Hz) photon emission via 3-inch crystal obelisks | Biological waveguide delivery |
| **Cymatic Acoustics** | "Nested 9" Distributed Mode Loudspeaker (DML) array | Physical standing waves through air and tempered glass |

---

## Repository Structure

```
/
├── index.html                  # Nested 9 Master Visualizer (central hub)
└── tools/
    ├── body_cad.html           # Body Alignment CAD
    ├── coil_cad.html           # Bifilar Coil Designer
    └── acoustic_cad.html       # Acoustic Placement Simulator
```

---

## Software Ecosystem

Use the tools in the following order for a complete bed design:

### 1. 🧍 Body Alignment CAD — `/tools/body_cad.html`

Maps human anatomy to the physical dimensions of the tempered glass bed.

- Proportional scaling to locate all **7 major endocrine/chakra points**
- Calculates physical constraints to prevent **4-inch copper coils** from overlapping
- Locks the **Crown node** to exactly **5.0"** from the top edge to harmonise with the DML acoustic canopy

---

### 2. 🔩 Bifilar Coil Designer — `/tools/coil_cad.html`

Simulates electromagnetic and thermal limits of the scalar coils.

- Calculates exact **wire lengths**, **electrical resistance**, and **amperage draw**
- Ensures the **5V 60A power supply** is not overloaded
- 3D simulation of Tesla's **"Constructive Series Stack"** topology
- Visualises the asymmetrical **4:1 Toroidal expansion** driving photons through the crystals

---

### 3. 🔊 Acoustic Placement Simulator — `/tools/acoustic_cad.html`

Designs the "Nested 9" DML speaker canopy.

- Maps spatial coordinates of the **9 tactile/acoustic exciters**
- Calculates **phase alignment** for constructive (not destructive) standing waves
- Targets **174 Hz sub-bass** and **7.83 Hz Schumann resonance** directly over the patient's spine

---

### 4. 🌐 Nested 9 Master Visualizer — `index.html`

The central hub. Imports output data from all three sub-tools.

- Macro-level **3D real-time visualisation** of the entire completed cocoon
- Shows live interaction between **magnetic fields**, **acoustic waves**, and **optical lasers**

---

## Hardware Wiring Reference

### 💡 Optical Array (Lights)

| Component | Specification |
|---|---|
| LEDs | 60× 3W |
| Drivers | Mean Well LDD-1000LW Constant Current |
| Topology | 5S2P |
| Power Supply | 24V |

### 🌀 Scalar Coil Array

| Component | Specification |
|---|---|
| Coils | 7× 16AWG Stacked Bifilar |
| Wiring | Series |
| Driver | Dual High-Power MOSFET |
| Protection | Flyback Diode + 10,000 µF decoupling capacitor |
| Power Supply | 5V 60A |

### 🎛️ Control System

Both arrays are **synchronously pulsed** via a multi-channel DDS Signal Generator:

- **Coils** → `7.83 Hz` (Schumann resonance)
- **Optics** → `16.5 Hz` (stroboscopic photon emission)

---

## Getting Started

1. Clone this repository:
   ```bash
   git clone https://github.com/your-org/nested-harmonic-cocoon.git
   cd nested-harmonic-cocoon
   ```

2. Open the tools in a browser — no build step required. All tools are self-contained HTML files.

3. Follow the [recommended tool order](#software-ecosystem) for a complete design workflow.

---

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

---

## License

[MIT](LICENSE)
