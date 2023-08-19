# Mesh-type-cell-models for PHITS
This program includes six types of mesh-type cell models and an input file for PHITS(> version 3.24).
Models described in the paper, "Multiple Mesh-type Real Human Cell Models for Dosimetric Application Coupled with Monte Carlo Simulations", published in Radiation Research.

# Input files
The node file and the element file are needed for TetGen format. 
The node file represents the serial number and 3D coordinates of the points in the tetrahedron geometry, with its suffix of “.node”; 
the element file denotes the index of facets composed of points in node files, with the suffix of “.ele”. 
The corresponding material for each facet was identified by the “universe” number in the Cell tally and the “mat” number in the Material tally in the ".inp" file.
Also, "tfile=Beas2B" in Line.63 of "Beas2B.inp" can be replaced with other cell names in the list.

Cell list in the "cell-models" folder:
1. Bronchial epithelial cell (Beas-2B): "Beas2B.ele" and "Beas2B.node".
2. Embryonic kidney cells (293T): "293T.ele" and "293T.node".
3. Epatocytes (L-02): "Lo2.ele" and "Lo2.node".
4. B-lymphoblastoid cells (HMy2.CIR): "HMY.ele" and "HMY.node".
5. Gastric mucosal cells (GES-1): "GES.ele" and "GES.node".
6. Intestinal epithelial cells (FHs74Int): "FHS.ele" and "FHS.node".




# Reference
Please cites these papers:
1. Yidi W et al., 2023, Multiple Mesh-type Real Human Cell Models for Dosimetric Application Coupled with Monte Carlo Simulations, RADIAT RES. DOI: 10.1667/RADE-23-00020.1.
2. Xianghui K et al., 2023, Microdosimetric assessment about proton spread-out Bragg peak at different depths based on the normal human mesh-type cell population model, PHYS MED BIOL. DOI: 10.1088/1361-6560/acec2b.




#
Please contact us if any questions via wangyidii@qq.com.
