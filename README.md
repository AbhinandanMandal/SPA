# An Energy-Feasible Parallel Algorithm for Large Dynamical Networks

Computation of shortest path algorithm has numerious real-world applications ranging from road networks, social networking, drone routing etc. This complexity reinforced when algorithm aims to optimize multiple objectives simultaniously. 

Imagine a scenario of military vehicle routing with energy-efficient drone assistant in rugged terrain. Effectively routing from one place to another one may needs to optimize multiple objectives for drone, such as *energy consumption*, *altitude change*, *wind uncertainty* etc.

<img width="727" height="462" alt="military_drone" src="https://github.com/user-attachments/assets/0c5fe90b-473e-49a4-a688-1b6947b3a04b" />


In the above example, finding the most suitable path is same as finding the most optimized path that satisfy all the necessary conditions for save traversal. 

## Contributions

To optimize the following multi-objective scenario, we propose energy-efficient `Greedy_SOSP` and multi-objective considering `Robust_MOSP` for large dynamical networks.

To analyze effectiveness and generalization, we tested following algorithms on a set of 8 datasets. 3 are from *Stanford Network Analysis Project (SNAP)* and 5 on-purpose generated from *OSMnx*, a package of **OpenStreetMap**.

### Dataset Statistics

| Dataset              | Total Vertices | Total Edges |
|----------------------|---------------:|------------:|
| roadNet-CA           | 1,965,206      | 5,533,214   |
| roadNet-TX           | 1,379,917      | 3,843,320   |
| roadNet-PA           | 1,088,092      | 3,083,796   |
| roadDrive-Bangalore  | 155,186        | 392,575     |
| roadDrive-Chennai    | 68,541         | 173,150     |
| roadDrive-Gwalior    | 40,187         | 102,233     |
| roadDrive-Kolkata    | 36,087         | 91,592      |
| roadDrive-Delhi      | 10,162         | 24,154      |


To check the efficiency, we further simulated `Greedy_SOSP`, `Robust_MOSP` with varying nodes and edge probability and find that `Greedy_SOSP` works `10.05x` faster than `Robust_MOSP`.

Runtime performance of `Greedy_SOSP`
<img width="2727" height="2153" alt="Greedy_SOSP_3D" src="https://github.com/user-attachments/assets/17c1041c-041f-480c-8678-9071b96ab569" />

Runtime performance of `Robust_MOSP`
<img width="2681" height="2153" alt="Robust_MOSP_3D" src="https://github.com/user-attachments/assets/46823dc0-c819-40df-a8ec-2a02fa1d1049" />





## Dataset
Dataset for the experiment can be downloaded from https://drive.google.com/file/d/1itJV5GkDe1sMRJD1GYerv27e1z3A_hso/view?usp=sharing




**Crafted with ☕ by Abhinandan**


