# Mesh-type-cell-models for PHITS
This program includes six types of mesh-type cell models and an input file for PHITS(> version 3.24).
Models described in the paper, "Multiple Mesh-type Real Human Cell Models for Dosimetric Application Coupled with Monte Carlo Simulations", published in Radiation Research.

# Input files
The node file and the element file are needed for TetGen format. 
The node file represents the serial number and 3D coordinates of the points in the tetrahedron geometry, with its suffix of “.node”; the element file denotes the index of facets composed of points in node files, with the suffix of “.ele”. The corresponding material for each facet was identified by the “universe” number in the Cell tally and the “mat” number in the Material tally.



# Reference
Please cites these papers:
1. Yidi W et al., 2023, Multiple Mesh-type Real Human Cell Models for Dosimetric Application Coupled with Monte Carlo Simulations, RADIAT RES. DOI: 10.1667/RADE-23-00020.1.
2. Xianghui K et al., 2023, Microdosimetric assessment about proton spread- out Bragg peak at different depths based on the normal human mesh-type cell population model, PHYS MED BIOL. DOI: 10.1088/1361-6560/acec2b.
