# Base code for accepted paper in International Conference on Industrial and Information Systems (ICIIS) 2026

Computation of shortest path algorithm has numerious real-world applications ranging from road networks, social networking, drone routing etc. This problem is further complicated when an algorithm targets the simultaneous optimization of multiple objectives.

Consider the following operation where energy-efficient UAV involved in assisting of military vehicle navigation in harsh terrain. Effectively routing from one place to another needs to consider various objective like energy, altitude, wind etc.

<img width="727" height="462" alt="military_drone" src="https://github.com/user-attachments/assets/0c5fe90b-473e-49a4-a688-1b6947b3a04b" />


In following above scenario, finding the efficient path is same as finding the most optimized path that satisfy all the necessary conditions for save traversal. 

## Contributions
Our contribution of this research work are,

1. To optimize the following various objective scenario, we propose energy-efficient `SOSP` algorithm and multi objective `MOSP` algorithm for large dynamical networks.

2. To analyze effectiveness and generalization, we tested following algorithms on a set of 8 datasets. 3 taken from [Stanford Network Analysis Project (SNAP)](https://snap.stanford.edu/data/index.html) and 5 generated from [OSMnx](https://osmnx.readthedocs.io/).


3. To check the efficiency, we further simulated proposed `SOSP` and `MOSP` algorithm with changing nodes and edge probability. Our findings proved that proposed`SOSP` algorithm is `10.05x` efficient than `MOSP` algorithm.

Runtime performance of proposed `SOSP` algorithm
<img width="2727" height="2153" alt="Greedy_SOSP_3D" src="https://github.com/user-attachments/assets/17c1041c-041f-480c-8678-9071b96ab569" />

Runtime performance of proposed `MOSP` algorithm
<img width="2681" height="2153" alt="Robust_MOSP_3D" src="https://github.com/user-attachments/assets/46823dc0-c819-40df-a8ec-2a02fa1d1049" />


## Dataset Availability
Dataset for the experiment can be downloaded from https://drive.google.com/file/d/1itJV5GkDe1sMRJD1GYerv27e1z3A_hso/view?usp=sharing


**Crafted with ☕ by Abhinandan**

