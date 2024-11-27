---
title: "[Review] VAD Impeller Design"
excerpt: "Prototype Design of a high-performance impeller in the pump of a Ventricular Assist Device (VAD). <br/><img src='../images/impeller_design/main.png'>"
collection: portfolio
order: 10
---

## Introduction

This design project focuses on developing a high-performance impeller in the pump of a Ventricular Assist Device (VAD). This device assists hearts failing from cardiovascular diseases (e.g., congestive heart failure). Currently, the design focuses on assisting the left ventricle for relatively long periods (e.g., decades). The goal is to meet stringent requirements for efficiency, durability, and biocompatibility while remaining economically viable for production.

<figure style="text-align: center;">
  <img src="../../images/impeller_design/vad_demonstration.png" alt="VAD Demonstration" style="max-width: 100%;" />
  <figcaption style="text-align: center; font-style: italic; color: #555;">Figure 1: Diagram of Ventricular Assist Device (VAD) components</figcaption>
</figure>


## Design

- **Operating Parameters**:
  - Continuous operation for a decade.
  - Pumps blood at 75 liters/min with a pressure difference of 0.80 bar.
- **Materials**:
  - Lightweight and biocompatible.
  - Chosen for compatibility with fluids and organs in the human body.

Each team member explored impeller designs at various speeds (2400-3000 rpm), optimizing parameters such as blade height, slip factor, and velocity match. We used Excel and MATLAB for calculations and Fusion 360 for CAD modeling. Materials were selected using CES for biocompatibility, strength, and thermal properties.

### Final Recommendations:
- **Mechanical Design**: 5-blade impeller, optimal speed at 2900 rpm.
- **Material**: Titanium ASTM F-136 (high biocompatibility, corrosion resistance).
  - Density: 4.41 g/cm³
  - Young’s Modulus: 110-119 GPa
  - Yield Strength: 786-910 MPa
- **Manufacturing Process**: Investment casting.

<div style="display: flex; justify-content: center; gap: 40px; align-items: flex-start; flex-wrap: nowrap;">
  <figure style="text-align: center; margin: 0;">
    <img src="../../images/impeller_design/cad_model.png" alt="CAD Model" style="max-width: 100%; height: 300px; width: 300px; margin: 0 auto;" />
    <figcaption style="font-style: italic; margin-top: 8px;">Figure 2: CAD Model</figcaption>
  </figure>

  <figure style="text-align: center; margin: 0;">
    <img src="../../images/impeller_design/investment_casting.png" alt="Investment Casting Schematic" style="max-width: 100%; height: 300px; width: 300px; margin: 0 auto;" />
    <figcaption style="font-style: italic; margin-top: 8px;">Figure 3: Investment Casting Schematic</figcaption>
  </figure>
</div>



## Evaluation

The prototype was manufactured using investment casting and 3D printing (see figure below). Tests showed exceptional pumping efficiency under high-pressure conditions, outperforming other designs.

<div style="display: flex; justify-content: center; gap: 40px; align-items: flex-start; flex-wrap: nowrap;">
  <figure style="text-align: center; margin: 0;">
    <img src="../../images/impeller_design/3d_printed_prototype.png" alt="3D Printed Prototype" style="max-width: 100%; height: 250px; width: 350px;" />
    <figcaption style="font-style: italic; margin-top: 8px;">Figure 4: 3D Printed Prototype</figcaption>
  </figure>

  <figure style="text-align: center; margin: 0;">
    <img src="../../images/impeller_design/performance_results.png" alt="Performance Results" style="max-width: 100%; height: 260px; width: 900px;" />
    <figcaption style="font-style: italic; margin-top: 8px;">Figure 5: Performance Results</figcaption>
  </figure>
</div>


## Conclusion

The proposed impeller design meets all functional, economic, and environmental criteria, offering a viable solution for long-term ventricular support. Future work could refine the flow dynamics and explore alternative manufacturing methods for enhanced scalability.
