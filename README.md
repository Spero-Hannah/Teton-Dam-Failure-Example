# Teton-Dam-Failure-Example
This repository contains both HEC-RAS and GeoClaw Teton Dam failure models, supplementary to the paper: Spero, H., Calhoun, D., and Schubert, M. (2022). "Simulating the 1976 Teton Dam Failure using GeoClaw and HEC-RAS and comparing with Historical Observations".

**1. Citation of the GitHub Repository:** Calhoun, D. and Spero, H. Teton Dam GeoClaw Repository. DOI: 000000000. Version 1. Zenodo Link.

**2. Description of the model:** To support reproducibility, a full description of the [GeoClaw](http://www.clawpack.org/geoclaw) and [HEC-RAS](https://www.hec.usace.army.mil/software/hec-ras/documentation/HEC-RAS_5.0.7_Release_Notes.pdf) softwares are available in their respective manuals (linked). Both models use a combined topography formed by: (I) USGS 30-m resolution for the larger topography and (II) USGS 15-m resolution topography. These terrains are sourced from (dd.cr.usgs.gov). 

**3. Information about the configuration/parameters used to run the model:** The authors provide the scripts and workflow used for this study. For GeoClaw: The configuration and parameters are included in the (I) maketopo.py file, (II) setrun.py, (III) setplot.py, (IV) reservoir polygon file, and the (V) gauges (stationary and Lagrangian). Further, an example maketopo.py file is included so users will be able to simulate identical simulations. These are in the GeoClaw section of the repository.
For HEC-RAS: The plan file for the HEC-RAS portion of this study is included in the repository, along with a Zip folder containing: (I) .p01 - plan file, (II) .g01 - Geometry file, (III) .f01 - Steady Flow file, (IV) r01 - the Run file, and (V) .O01 - an example output file. These are the files necessary for running the HEC-RAS simulations. These files are in the HEC-RAS portion of the repository. The sensitivity analysis parameters are outlined in the methods portion of the paper and can be easily amended from the provided files.

**4. Data that supports summary results, tables, and figures:**
The 'Teton-Dam-Failure-Example' section of the GeoClaw code is amended from the general Clawpack package (available at https://github.com/clawpack; https://github.com/clawpack/geoclaw). Workflows and scripts for the open-source GeoClaw provided by LeVeque, R., Mandli, K., Calhoun, D., Ketcheson, D., and others. Summary files that support the research, figures, and tables are included in this repository (example output files from both GeoClaw and HEC-RAS are included in this repository because the data is instrumental to evaluating the research).

