# Teton-Dam-Failure-Example
This repository contains both HEC-RAS and GeoClaw Teton Dam failure models, supplementary to the paper: Spero, H., Calhoun, D., and Schubert, M. (2022). "Simulating the 1976 Teton Dam Failure using GeoClaw and HEC-RAS and comparing with Historical Observations".

1. Citation of the model: Calhoun, D. and Spero, H. Teton Dam GeoClaw Repository. DOI: 000000000. Version 1. Link available at: insert website link.

2. Description of the model: To support reproducibility, a full description of the GeoClaw and HEC-RAS models is included. Both models use two topographies: (I) USGS 30-m resolution for the larger topography and (II) USGS 15-m resolution topography. Both of those terrains are sourced from (insert website link). 

3. Information about the configuration/parameters used to run the model: The authors provide the script and workflow used for this study. For GeoClaw: The configuration and parameters are included in the (I) maketopo.py file, (II) setrun.py, (III) setplot.py, (IV) reservoir polygon file, and the (V) gauges (stationary and Lagrangian). Further, an example maketopo.py file is included so users will be able to simulate identical simulations.
For HEC-RAS: The plan file for the HEC-RAS portion of this study is included in the repository, along with a Zip folder containing: (I) .p01 - plan file, (II) .g01 - Geometry file, (III) .f01 - Steady Flow file, (IV) r01 - the Run file, and (V) .O01 - an example output file. These are the files necessary for running the HEC-RAS simulations. The sensitivity analysis parameters are outlined in the methods portion of the paper and can be easily amended from the provided files.

4. Data that supports summary results, tables, and figures:
The 'dam flooding' section of the GeoClaw code is amended from the general Clawpack package (available at https://github.com/clawpack; https://github.com/clawpack/geoclaw). Workflows and scripts for the open-source GeoClaw provided by LeVeque, R., Mandli, K., Calhoun, D., Ketchum, D., and others. Summary files that support the research, figures, and tables are included in this repository (example output files from both GeoClaw and HEC-RAS are included in this repository because the data is instrumental to evaluating the research.
