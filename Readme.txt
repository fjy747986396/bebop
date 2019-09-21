In these folders, you may find:

Experimental data:
All data files as well as Matlab scripts to manipulate/visualize the experimental data.

Generate Tree:
The main Matlab files required to reproduce the simulation-based LQR-Tree policies discussed in the paper. In the subfolders, you may find the generated control policies discussed in the paper.

helpers:
Matlab functions that display tree statistics or that generate the basin of attraction plot shown in the paper. Furthermore, you may find other auxiliary Matlab functions used for plotting and the mex files that we use to query the tree-policy on the experimental setup / we use when generating the tree.

Run Tree:
Contains Matlab functions that you may use to simulate random initial conditions with the tree policies contained in Generate Tree, and to extract the policy quality-measures described in Sec. 4.5.
