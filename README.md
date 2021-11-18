# `DockStreamCommunity`

## Description
This repository is meant to store `Jupyter Notebook` tutorials and documentation for [DockStream](https://github.com/MolecularAI/DockStream). 

## Supported Backends
### Ligand Embedders
* **[`RDKit`](https://www.rdkit.org/docs/GettingStartedInPython.html#working-with-3d-molecules)**
* **[`Corina`](https://www.mn-am.com/products/corina)**
* **[OpenEye's `OMEGA`](https://www.eyesopen.com/omega)**
* **[Schrodinger's `LigPrep`](https://www.schrodinger.com/products/ligprep)**
* **[`TautEnum`](https://github.com/OpenEye-Contrib/TautEnum/blob/master/README)**

### Docking Backends
* **[`AutoDock Vina`](http://vina.scripps.edu/index.html)**
* **[`rDock`](http://rdock.sourceforge.net)**
* **[OpenEye's `Hybrid`](https://www.eyesopen.com/oedocking-tk)**
* **[Schrodinger's `Glide`](https://www.schrodinger.com/glide)**
* **[CCDC's `GOLD`](https://www.ccdc.cam.ac.uk/solutions/csd-discovery/components/gold)**

Note, that the `CCDC` package, the `OpenEye` toolkit and `Schrodinger`'s tools require you to obtain the respective software from those vendors.

## Using DockStream in REINVENT
DockStream provides a flexible implementation of molecular docking as a scoring function component in REINVENT. The generative 
agent is able to gradually generate compounds that satisfy the DockStream component, i.e, achieve favourable docking scores. 
A [tutorial notebook](https://github.com/MolecularAI/ReinventCommunity/blob/master/notebooks/Reinforcement_Learning_Demo_DockStream.ipynb) is provided.

## Requirements
A Conda environment is provided: `DockStreamCommunity` via `environment.yml` to execute the `Jupyter Notebook` tutorials. 
Some notebooks also require the `DockStream` and `DockStreamFull` environments to be installed 
(see [DockStream README](https://github.com/MolecularAI/DockStream)). 
```
git clone <DockStreamCommunity repository>
cd <DockStreamCommunity directory>
conda env create -f environment.yml
conda activate DockStreamCommunity
jupyter notebook
```

## Contributors
Christian Margreitter (christian.margreitter@astrazeneca.com)
Jeff Guo (jeff.guo@astrazeneca.com)
Alexey Voronov (alexey.voronov1@astrazeneca.com)