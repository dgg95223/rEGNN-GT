# rEGNN-GT for excited-state properties prediction
This is a graph transformer based on the architecture of GraphGPS.
A revised EGNN, rEGNN, is adopted as the MPNN module to capture the local environment of atom.
Transformer is used to provide non-local information that beyond the local cutoff.
The two branches match the fact that excited-state properties are affected by the local and non-local characters at the same time.
