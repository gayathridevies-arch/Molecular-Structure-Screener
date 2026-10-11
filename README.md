# Molecular-Structure-Screener
Automated molecular screening and structural feature extraction pipeline built with Python, Pandas, and RDKit.
# Automated Molecular Structure Screening & Visualization Pipeline

A clean, efficient Python workflow for batch screening and visualizing molecular datasets using **RDKit** and **Pandas**. 

This project automates the structural analysis of small molecules by looping through custom SMARTS query blueprints, flagging functional groups, filtering datasets, and rendering structural grid visualizations.

## Key Features
- **Automated Multi-Pattern Screening:** Uses a dictionary-based loop to screen for multiple functional groups simultaneously (`Has_Benzene`, `Has_Carbonyl`, `Has_Hydroxyl`).
- **SMARTS Pattern Matching:** Utilizes RDKit's graph-based chemical parsers (`Chem.MolFromSmarts` and `HasSubstructMatch`) for precise structural identification.
- **Data Filtering & Aggregation:** Demonstrates Boolean indexing in Pandas to filter complex chemical subsets and calculate multi-condition matches.
- **Structural Visualization:** Leverages RDKit's grid-drawing tools (`MolsToGridImage`) to cleanly display molecular subsets.

## Tech Stack
- **Python**
- **RDKit** (Cheminformatics & Molecular Processing)
- **Pandas** (Data Manipulation & Analysis)

## Quick Start
1. Clone the repository or open the notebook in Google Colab.
2. Install the required dependencies:
   ```bash
   pip install rdkit pandas
