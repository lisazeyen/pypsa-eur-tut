# PyPSA-Eur-Tutorial
 ### Light-weighted conda environment and small examples for the PyPSA-Eur-Tutorial at Openmod

--------------------------------------------------------------------------------------------------------------------------
PyPSA-Eur is an open model dataset of the European power system at the transmission network level that covers the full ENTSO-E area. The model is suitable both for operational studies and generation and transmission expansion planning studies. The continental scope and highly resolved spatial scale enables a proper description of the long-range smoothing effects for renewable power generation and their varying resource availability.

The model is described in the documentation and in the paper PyPSA-Eur: An Open Optimisation Model of the European Transmission System, 2018, arXiv:1806.01613.

------------------------------------------------------------------------------------------------------------------------------

This is a light-weighted version only for the [PyPSA-Eur Tutorial](https://forum.openmod-initiative.org/t/tutorial-getting-started-with-pypsa-eur-an-open-optimisation-model-of-the-european-power-transmission/1790) at the Openmod and not efficient for the whole workflow. To set up the environment for the Tutorial: 

:one: **clone or download** the data from the repository 

:two:  Pypsa-eur relies on a set of other Python packages. The easiest way to install them is to use **conda** (an environment        management system). If conda is not already installed on your system, you can install miniconda by following the                installation [guide](https://docs.conda.io/projects/conda/en/latest/user-guide/install/) 

:three: Open a terminal and cd to the cloned/downloaded repository pypsa-eur-tut and install the environment with
	<p align="center">
	   **some_other_path/pypsa-eur-tut$ conda env create -f environment.yaml**
	
:four: download some already **solved networks** from 
       https://drive.google.com/drive/folders/16CFGKj1GBfjEQbweqi5VD0fLuLwTB6Im?usp=sharing \
       and save them in in your folder pypsa-eur-tut

Now you are ready to start with the tutorial :smirk:! 
  
