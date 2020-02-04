# MultidimSynapticProteins

This repository contains all scripts that were used to generate the results in the paper : _Activity-dependent remodelling of synaptic protein organization revealed by high throughput analysis of STED nanoscopy images_.

To facilitate the usage of the `MultidimSynapticProteins` we provide the user with a `Jupyter Notebook`. We recommend a new user following the steps in at this [link](https://jupyter.readthedocs.io/en/latest/running.html) to run the provided notebook. The notebook, scripts and data used are all provided in the `/src` folder.

# Required packages 

import numpy 
import os
import warnings
import matplotlib 
import pickle 

from IPython.display import display, HTML
from scipy import signal
from scipy.spatial import distance
from skimage import morphology
from collections import defaultdict

from umap import UMAP

from matplotlib import pyplot, lines
from mpl_toolkits.mplot3d import Axes3D

# Run example data

We provide to the user a small amount of data to run the notebook from its own computer. 

# Reference
```
@article{Wiesner2020,
  title={Activity-dependent remodelling of synaptic protein organization revealed by high throughput analysis of STED nanoscopy images},
  author={Wiesner, Theresa and Bilodeau, Anthony and Bernatchez, Renaud and Raulier, Bastian and De Koninck, Paul and Lavoie-Cardinal, Flavie},
  journal={Frontiers in Neural Circuits},
  volume={},
  number={},
  pages={},
  year={2020},
  publisher={Frontiers}
}
```
