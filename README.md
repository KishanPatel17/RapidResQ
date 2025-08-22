# RapidResQ 🚒🔥
RapidResQ is a firefighter-focused GIS mapping app built in C++ (ECE297, UofT). Features include hydrant/building/weather layers, night mode, A routing, and optimization. Designed for speed, clarity, and split-second decision making. (Docs only)

> **Note**: This repository documents the project only. **Source code is not included** per course policy.

## Overview
RapidResQ is an emergency response tool that gives firefighters **fast, clear, and reliable** access to the information they need under pressure. Built for **ECE297 (Software Design & Communication, University of Toronto)**, it combines a **usability-first map UI** with **routing and optimization algorithms** to support split‑second decisions.

Our mission: **help first responders prepare, act, and respond with confidence.**

---

## Features
### 🔑 Usability & UI
- **Layer Toggles**: Quickly show/hide weather, hydrants, and building heights.
- **Night Mode**: Improves readability in low light and while driving.
- **High-Contrast Icons & Colours**: Distinguish hydrants, POIs, and building layers at a glance.
- **Dynamic Level of Detail (LOD)**: Zoom-based rendering (highways → hydrants) cuts visual clutter.
- **Scale Bar & Legends**: Better spatial awareness for pre‑planning.
- **Survey-Validated**: Usability survey returned a **91% score**.

### 🚰 Critical Data Layers
- **Fire Hydrants**: Locations with details (pressure, type, water source).
- **Buildings**: Heights and material context for vertical access planning.
- **Weather**: Contextual data for attack strategy (wind, precipitation, etc.).

### 🧭 Smart Navigation
- **Autocomplete Search**: Real-time suggestions for addresses/streets.
- **A* Pathfinding**: Fast, optimal routing tuned for emergency response.

### ⚡ Optimization
- **Ant Colony Optimization (ACO)**: Generates strong initial routes.
- **2‑Opt & Or‑Opt**: Local refinements to decrease overall travel time.
- **Multithreading**: Improves responsiveness under heavier loads.
- **Render Efficiency**: **25–50%** reduced render times; typical frame under **100 ms**.

### 🔥 Fire Spread Simulation *(Planned)*
Predictive model using **wind, weather, terrain, and materials** to highlight **high‑risk zones** and improve evacuation and containment planning.

---

## Technical Highlights
- **Language**: C++ (course framework)
- **Pathfinding & Optimization**: A*, Ant Colony, 2‑Opt, Or‑Opt
- **Rendering**: Dynamic, zoom-aware selective rendering
- **UX Validation**: Survey, button-driven layer control, night mode

---

## Demos & Screenshots

- Hydrants & details  
  ![Hydrants](media/hydrants.png)
- Building heights with legend  
  ![Building Heights](media/building-heights.png)
- Night mode & high-contrast iconography  
  ![Night Mode](media/night-mode.png)
- Autocomplete + A* routing  
  ![Autocomplete](media/autocomplete.png)

---

## Performance & Usability
- **Render time**: 25–50% reduction vs. baseline; typical frame < 100 ms.
- **Clarity-first design**: Buttons, legends, and high-contrast colour choices.

---

## Team
**Kishan**, **Sahib**, **Davina**  
University of Toronto — **ECE297: Software Design & Communication**

---

## Acknowledgements
- Course staff for framework and datasets
- External references on usability, response times, and fire modelling
- Fire service community for inspiration and feedback

---

## License
This repository contains **documentation and media only**. No source code is distributed.
Unless otherwise noted, text and images © the authors. For educational use.
