# 2D Cloud Chamber Simulation

An interactive 2D physics simulation of a Wilson cloud chamber built with **p5.js** and vanilla JavaScript. This project models supersaturated vapor condensation, particle-matter interactions, and electromagnetic deflection in real time.

![Simulation Preview](https://img.shields.io/badge/Physics-Particle%20Simulation-blue) ![p5.js](https://img.shields.io/badge/Library-p5.js%20v1.9.0-ed225d) ![License](https://img.shields.io/badge/License-MIT-green)

## 🚀 Live Demo

[Play with the Simulation](https://thomasrblaise-ui.github.io/Cloud-chamber-1.0/)

## ✨ Key Features

- **Radioisotope Sources**: Selectable radioactive emitters (Am 241, Sr 90, Co 60, Natural U 238, Ra 226) with adjustable activity ( 0 to 10 Bq).
- **Cosmic Radiation**: Toggleable cosmic muon atmospheric background tracks.
- **Lorentz Force Deflection**: Real-time trajectory bending under a variable perpendicular magnetic field (B = -50 T to +50 T).
- **Accurate Particle Physics**:
  - **Alpha Particles (alpha)**: Heavy, short range, high ionization rate with **Bragg peak** density amplification at track ends.
  - **Beta Particles (beta-)**: Light, erratic paths due to Coulomb scattering.
  - **Muons (mu)**: High-momentum, minimal scattering trajectories with random charge states ($\pm q$).
- **Droplet Dynamics**: Droplet condensation along particle ion trails, including realistic gravity drift and opacity decay.

## 🛠️ Built With

* **HTML5 / CSS3** (Custom dark-mode UI panel)
* **JavaScript (ES6+)**
* **[p5.js v1.9.0](https://p5js.org/)** — Canvas rendering and vector math engine

## ⚡ How to Run Locally

Because this is a standalone single-file project, no node modules or build processes are required.

1. Clone the repository:
   ```bash
   git clone [https://github.com/thomasrblaise-ui/NOM-DE-TON-DEPOT.git](https://github.com/thomasrblaise-ui/NOM-DE-TON-DEPOT.git)
