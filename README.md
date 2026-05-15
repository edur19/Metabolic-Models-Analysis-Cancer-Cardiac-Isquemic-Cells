# Metabolic-Models-Analysis-Cancer-Cardiac-Isquemic-cells


# Metabolic Modeling and Clustering Analysis using COBRA Toolbox

## Overview
Practices realized during the course "Metabolic Systems" in the Master of Bioengineering and Intelligent Computing at CUCEI.
This repository contains tutorials, practice workflows, and research-oriented projects developed to learn and apply the COBRA Toolbox for metabolic modeling, as well as clustering techniques and interactive data visualization for metabolic flux analysis.

The projects focus on the analysis of metabolic behavior during biomass production under different reaction constraints using MATLAB, Python, Dash, and machine learning approaches.

---

# Repository Structure

## `tutorials/`
Contains tutorial workflows and practice exercises used to learn the fundamentals of the COBRA Toolbox in MATLAB.

Topics include:
- Environment setup
- Model loading and preprocessing
- Reading metabolic models
- Adding and modifying reactions
- Flux Balance Analysis (FBA)
- Basic metabolic simulations

---

## `kmeans_input_data.xlsx`
Contains metabolic flux data generated during the closure of specific metabolites and exchange reactions during biomass production simulations.

The dataset was used for clustering analysis and interactive visualization of metabolic behavior.

---

## `Dashboard_Breast_Cancer_Cell.py`
<img width="1013" height="650" alt="image" src="https://github.com/user-attachments/assets/aab35f74-2406-4345-aaa5-c06a0740f238" />

Contains an interactive dashboard developed using Dash and Plotly for the exploration and visualization of metabolic fluxes.
The dashboard allows:
- Interactive reaction selection
- Visualization of biomass production changes
- Exploration of metabolic dependencies
- Dynamic analysis of reaction impact on cellular growth

---

## `K_means_in_Breast_Cancer_Cell.ipynb`
<img width="464" height="273" alt="image" src="https://github.com/user-attachments/assets/5441600e-0529-4cd0-8165-aecad557d7d5" />

Contains an unsupervised machine learning workflow using the K-Means clustering algorithm to identify metabolic patterns and groups of reactions based on flux behavior.
The notebook includes:
- Data preprocessing
- Feature normalization
- Elbow Method analysis
- K-Means clustering
- Interactive 3D visualization of metabolic reaction clusters

---

# Results
The interactive dashboard revealed heterogeneous metabolic behavior across different metabolite perturbations. Each point in the visualization represents biomass production after constraining or closing a specific metabolic reaction.

Several amino acids, including leucine and asparagine, were identified as essential metabolites for biomass production, as their removal resulted in near-zero cellular growth.

These findings are consistent with previously reported literature and demonstrate the capability of genome-scale metabolic models to reproduce biologically relevant phenotypes in silico.

The clustering analysis further identified groups of reactions with similar metabolic behavior, providing insights into potential metabolic dependencies and coordinated pathways associated with cellular growth.
