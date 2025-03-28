# MindWandering
Code to reproduce figures in ["Inferring Mind Wandering from Perceptual Decision Making"](http://osf.io/preprints/psyarxiv/mxtbh_v2) from Zhang and Kool (2025). 

Before running notebooks for specific figures, you should run the files in "Data preprocessing" to generate the data file needed for later analysis.


Systems requirements can be found in the file requirements.txt. 

For fitting multi-state GLM-HMM, We followed the analysis procedure in work from [Ashwood et al. (2022)](https://doi.org/10.1038/s41593-021-01007-z) and followed the setup guidelines provided by the authors [here] (https://github.com/zashwood/glm-hmm/tree/main). Accordingly, to install the version of `ssm` used in our work, follow the instructions provided there, namely: 
    
```
cd ssm
pip install numpy cython
pip install -e .
```

For fitting HDDM, we followed installation guidelines provided by the developers of the package [here] (https://github.com/hddm-devs/hddm). In addition, refer to requirements_hddm.txt in the folder "Figure3_HDDM" for system requirements.
