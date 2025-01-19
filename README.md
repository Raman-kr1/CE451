# Sheet Pile Wall Design Analysis

This repository contains the analysis of a sheet pile wall design using finite element software PLAXIS, conducted as part of a term project. The project involves validating numerical results with benchmark studies and assessing the impact of seepage flow and soil properties on wall stability.

---

## Project Overview

- **Objective:**
  Analyze the design of a sheet pile wall subjected to groundwater flow and compare the results with the study by Benmebarek et al. (2006).

- **Key Goals:**
  - Simulate active and passive earth pressures under varying seepage conditions.
  - Evaluate the effects of hydraulic gradients, soil friction angle, and dilation angle on wall stability.
  - Validate results using the Mohr-Coulomb soil behavior model and compare them with benchmark data.

---

## Methodology

1. **Finite Element Modeling:**
   - Software: PLAXIS 2D
   - Soil Behavior Model: Mohr-Coulomb
   - Key Parameters: Friction angle, dilation angle, permeability, and unit weight of soil.

2. **Simulations:**
   - Modeled seepage effects using hydraulic gradients across the wall.
   - Applied boundary conditions and meshing techniques for accuracy.
   - Assessed displacement fields, stress distribution, and pore pressure variations.

3. **Validation:**
   - Compared results with benchmark study (Benmebarek et al., 2006).
   - Verified active/passive earth pressure coefficients and failure mechanisms.

---

## Results

- Reduced passive pressures and increased active pressures due to seepage flow.
- Significant impact of dilation angle and hydraulic head loss on stability.
- Close agreement with benchmark study, validating the numerical approach.

---

## Repository Structure

```plaintext
|-- data/             # Input files and parameters used in PLAXIS simulations
|-- results/          # Simulation output files (stress distribution, displacement fields, etc.)
|-- scripts/          # Python scripts for data visualization and result processing
|-- references/       # Supporting literature and papers
|-- README.md         # Project documentation
```

---

## Usage

1. **Prerequisites:**
   - PLAXIS 2D software for running simulations.
   - Python (with Pandas, Matplotlib, and Numpy) for data analysis and visualization.

2. **Steps to Run:**
   - Use the input files in the `data/` directory to set up simulations in PLAXIS.
   - Analyze the results using provided scripts in the `scripts/` directory.

3. **Outputs:**
   - Stress distribution and displacement fields.
   - Plots of active/passive pressures vs. seepage conditions.

---

## References

1. Benmebarek, N., Benmebarek, S., Kastner, R., & Soubra, A.-H. (2006). Passive and active earth pressures in the presence of groundwater flow. *Géotechnique*, 56(3), 149–158.
2. PLAXIS Reference Manual.

---

## License

This project is licensed under the MIT License - see the LICENSE file for details.

---

## Contact

For any queries, reach out to [Your Name](mailto:your_email@example.com).
