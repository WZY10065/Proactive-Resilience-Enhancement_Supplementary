# IEEE-TII_Proactive Resilience Enhancement for Flexible Distribution Networks Containing Data Centers with Multiple Fault Phases Coupling_Supplementary

This repository contains supplementary files for the TII research paper. The files include data for case studies, additional methodological details, and a glossary of terms to support readers in understanding the main document.

## File Descriptions

1. **case_bus_40_F4.xlsx**
   - **bus**: This sheet lists bus data, including:
     - Power demand (`Pd` in MW, `Qd` in MVar)
     - Coordinates (`Coordinate_x`, `Coordinate_y`)
     - Substation flag (`Substation_Flag`), indicating whether a bus is part of a substation
     - Distributed Generation candidate status (`DG_candidate`)
     - Demand Response nodes (`DR_node`)
     - Workload capacity
   - **branch**: Details data on the connections (branches) between buses, including:
     - Resistance (`r`)
     - Reactance (`x`)
   - **parameter**: Defines system parameters such as:
     - Maximum power capacities (`S_max`, `DG_max`, `SS_max`)
     - Voltage limits (`U_R`, `U_min`)

2. **TII_Appendix.pdf**
   - This appendix document provides additional details on the methodology and equations used in the study, serving as a complement to the main research paper. It is recommended for readers who want a deeper understanding of the case study and model design.

3. **TII_Nomenclature.pdf**
   - Contains definitions and explanations of symbols, abbreviations, and terms used throughout the study, making it easier for readers to understand technical details.

## Usage

Each file is intended to aid in reproducing and understanding the case study results in the main paper. The Excel file provides essential data inputs, while the PDF documents offer explanatory content and definitions.

---

Feel free to explore the files for more detailed information related to each component of the case study.
