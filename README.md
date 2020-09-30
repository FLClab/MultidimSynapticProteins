# MultidimSynapticProteins

This repository contains all scripts that were used to generate the results in the paper : _Activity-dependent remodelling of synaptic protein organization revealed by high throughput analysis of STED nanoscopy images_.

To facilitate the usage of the `MultidimSynapticProteins` we provide the user with a __Jupyter Notebook__. We recommend new users to follow the steps at this [link](https://jupyter.readthedocs.io/en/latest/running.html) to run the provided notebook. Users familiar with a __Jupyter Notebook__ can verify the [required packages](#required-packages) and jump to the [run example data](#run-example) section. The notebook, scripts and data used are all provided in the `/src` folder.

<a id="required-packages"></a>
# Required packages 

To facilitate the installation of the packages we creates a `requirements.txt` file containing all necessary packages. The users can validate that they have all required packages using this command
```bash
pip install -r requirements.txt --upgrade
```

<a id="run-example"></a>
# Run example data

We provide to the user a small amount of data to run the notebook from its own computer. To launch the __Jupyter Notebook__ the users should enter the following command
```bash
jupyter notebook
```

In the _Define constants_ section of the __Jupyter Notebook__ users can modify the parameters of the analysis pipeline. The other sections are self-explanatory and well commented to allow the users to follow the analysis.

# Reference

Please cite this analysis pipeline by using the provided bibtex entry or citation.

> Wiesner T, Bilodeau A, Bernatchez R, Deschênes A, Raulier B, De Koninck P and Lavoie-Cardinal F (2020) Activity-Dependent Remodeling of Synaptic Protein Organization Revealed by High Throughput Analysis of STED Nanoscopy Images. Front. Neural Circuits 14:57. doi: 10.3389/fncir.2020.00057

```
@article{Wiesner2020,
  title={Activity-dependent remodelling of synaptic protein organization revealed by high throughput analysis of STED nanoscopy images},
  author={Wiesner, Theresa and Bilodeau, Anthony and Bernatchez, Renaud and Raulier, Bastian and De Koninck, Paul and Lavoie-Cardinal, Flavie},
  journal={Frontiers in Neural Circuits},
  volume={14},
  pages={57},
  year={2020},
  doi={10.3389/fncir.2020.00057},
  publisher={Frontiers}
}
```
