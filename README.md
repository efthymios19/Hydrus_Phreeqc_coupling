# Hydrus Phreeqc coupling

This repository hosts the source code (python) code of coupling between Hydrus and Phreeqc. The code is presented in .ipynb notebook and it is developed as supplementary material to the manuscript "Transport and fate of Per- and polyfluorinated alkyl substances (PFAS) in urban environments: A holistic modeling approach with free and open-source software.". 

Hydrus input data and final simulation is achieved by using the [Phydrus](https://github.com/phydrus/phydrus) python package. Source code of Phydrus has been developed for 4.08 version of Hydrus1D and the code can be retrieved and compiled for every os from a dedicated [repository](https://github.com/phydrus/source_code). For the purposes of this study the source code was compiled for macos, with technical characteristics:
Chip: Apple M3
Memory: 16 GB

Phreeqc simulation was achieved through the [PhreeqPy](https://www.phreeqpy.com/) and in particular with IPhreeqc interface without the need to run a COM server and therefore also works on non-Windows systems.

For the complete list of python version and packages/libraries versions used in the .ipynb, refer to the [requirements.txt](requirements.txt) file.
