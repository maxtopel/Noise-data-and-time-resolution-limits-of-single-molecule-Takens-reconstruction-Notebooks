# Noise data and time resolution limits of single molecule Takens reconstruction notebooks
Example jupyter notebooks detailing the simulation and reconstruction of synthetic noisy time series trajectories from molecular dynamics training data.

Run in order:
1) 0: extract head to tail distances and time averaged trajectories ((a) to (b)). 
2) 1: Learn low dimensional representations of these trajectories ((a) to (c)).
3) 3: Learn low dimensional representations of dynamics from noisy time averaged head to tail data ((b) to (d)).
4) 4: Learn intermanifold map between manifolds learned in 1 and 3 ((d) to (c)).
5) 5: Learn backmaping between reconstructed manifold learned in 4 and all atom positions ((c) to (e)).


![See Schematic](Schematic.pdf)
