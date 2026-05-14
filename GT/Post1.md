---
title: "Gas Turbines: Blog"
layout: default
---

# [Blog Post Title]

![Cover image or schematic](/assets/blog-cover-image.jpeg)

**Short intro (2–3 sentences):**  
[Briefly state the topic, why it matters, and what the reader will learn. Example:  
In this post, I share how I designed a compact gas turbine for a 150 kg tactical UAV, including cycle analysis, key trade-offs, and lessons learned from Python-based optimization.]

---

## Motivation

- Why this topic is important for UAV/aerospace engineering.
- How it connects to your work (M.Tech thesis, current UAV design, CFD projects).
- What problem you’re trying to solve (e.g., better SFC, higher cruise efficiency, weight reduction).

---

## Background & Theory

### Key Concepts

- Brief explanation of the core concept (e.g., gas turbine cycle, adjoint-based optimization, Raymer aircraft sizing).
- Any important equations (use LaTeX-style math if supported):

  \[
  w_c = c_p (T_{t3} - T_{t2}) = \frac{c_p T_{t2}}{\eta_c} \left[ \pi_c^{(\gamma-1)/\gamma} - 1 \right]
  \]

### Assumptions

- List modeling assumptions (steady flow, ideal gas, component efficiencies, etc.).

---

## Methodology

### Design Approach

- Tools used: Python, OpenFOAM, SU2, Excel, GT-API, etc.
- Workflow:  
  1. Conceptual sizing (Raymer)  
  2. 1D cycle analysis  
  3. Component design (compressor/turbine)  
  4. CFD validation / parametric studies

### Implementation Details

- Any custom scripts or algorithms (e.g., LUT-FADS, constraint analysis tool).
- How you structured the problem (inputs, outputs, optimization loop).

---

## Results

### Performance Summary

Use a table or bullet points:

| Parameter            | Value          |
|----------------------|----------------|
| Thrust / Power       | [value]        |
| SFC                  | [value]        |
| Overall Efficiency   | [value]        |
| Weight               | [value]        |

### Key Observations

- What worked well.
- What surprised you.
- Trade-offs you made (e.g., higher pressure ratio vs. weight/complexity).

Include plots or diagrams here if available:

![Cycle T-s diagram](/assets/ts-diagram.png)

---

## Discussion

- Compare your results with literature or baseline designs.
- Discuss limitations (simplified model, lack of 3D effects, etc.).
- Connect back to UAV system integration (mission profile, constraints, packaging).

---

## Lessons Learned

- Technical insights (e.g., how T<sub>t4</sub> drives SFC).
- Process insights (e.g., importance of modular code, version control).
- How this informs your current UAV design or future work.

---

## Future Work

- What you’d do next: higher-fidelity CFD, experimental validation, multi-objective optimization, certification analysis, etc.
- How this ties into your learning goals (systems engineering, advanced aerodynamics, startup ecosystem).

---

## References

- [1] Mattingly, J. D. *Elements of Gas Turbine Propulsion*.
- [2] Hill, P., & Petersen, C. *Mechanics and Thermodynamics of Propulsion*.
- [3] Your thesis, reports, or internal documents.

---

## Connect With Me

- [LinkedIn](https://linkedin.com/in/mohideen-ansar-aero)
- Email: [mohideenansara@gmail.com](mailto:mohideenansara@gmail.com)
- GitHub: [your-github-username]
