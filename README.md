# pypsa-eur-tut
Light-weighted conda environment and small examples for the PyPSA-Eur-Tutorial at Openmod

PyPSA-Eur is an open model dataset of the European power system at the transmission network level that covers the full ENTSO-E area. The model is suitable both for operational studies and generation and transmission expansion planning studies. The continental scope and highly resolved spatial scale enables a proper description of the long-range smoothing effects for renewable power generation and their varying resource availability.

The model is described in the documentation and in the paper PyPSA-Eur: An Open Optimisation Model of the European Transmission System, 2018, arXiv:1806.01613.

This is a light-weighted version only for the PyPSA-Eur Tutorial at the Openmod and not efficient for the whole workflow. To set up the environment for the Tutorial: 

1.) clone or download the data from the repository 

2.)  Pypsa-eur relies on a set of other Python packages. The easiest way to install them is to use conda (an environment management system). If conda is not already installed on your system, you can install miniconda by following the installation guide \url{https://docs.conda.io/projects/conda/en/latest/user-guide/install/} 

3.) Open a terminal and cd to the cloned/downloaded repository pypsa-eur-tut and install the environment with
	some_other_path/pypsa-eur-tut$ conda env create -f environment.yaml
  
