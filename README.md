# snapshot-POD
The following repository contains a Python implementation of the [snapshot POD](https://doi.org/10.1090/qam/910462) heavily inspired by the tutorial from [Julien Weiss](https://doi.org/10.2514/6.2019-3333).
Additional Python scripts for post-processing and plot generation are available here, including all the POD related plots presented in XXXXXXXXXXXXXXXXX.
In addition, all the POD-decomposition files and a sample of our instantaneous PIV velocity fields are available here.

# PIV_data
This folder contains the first 500 instantaneous velocity vectors from the nine experiments discussed and presented in XXXXXXXXX
Those results can be used to test our POD implementation.

# Snapshot_POD
This folder contains our Python-based snapshot POD script. 
It reads files from the PIV_data folder and generate the POD decomposition fields in a .npz format.

# POD_results
This folder contains the POD decomposition fields, with the full 2500 instantenous velocity fields, of the nine experiments discussed and presented in XXXXXXXXX.

# Post_processing
This folder contains the post-processing scripts that can generate most of the POD-related plots avaliable at XXXXXXXXXXXXXXXXX.

# Reference
The related article can be found at XXXXXXXXXXXXXXXXX.
