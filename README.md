# High confidence glycosomal membrane protein inventory unveils trypanosomal Peroxin PEX15


This repository contains data analysis script for the manuscript "High confidence glycosomal membrane protein inventory unveils trypanosomal Peroxin PEX15.".

## System requirements
- Scripts are provided as [Jupyter notebooks](https://jupyter.org/).
- Analysis was performed using modules from [the autoprot project](https://github.com/ag-warscheid/autoprot) which need to be installed on your local computer
  - Autoprot integrates Python and R scripts for proteomics data analysis and therefore requires both languages to be installed
- Software dependencies are detailed in the ''requirements.txt'' file in the autoprot repository
  - However, detailed information on all installed packages during execution including version numbers are provided in the respective notebooks (as ''environment.txt'' and ''R_environment.csv'' respectively)
- The scripts were tested with Python 3.10 and[LICENSE.md](https://github.com/user-attachments/files/18851660/LICENSE.md)
 R 4.2.2 on MS Windows 10 and Ubuntu 22.04 LTS.

## Installation guide
- Install autoprot on your local computer (see installation instructions on [the autoprot repository](https://github.com/ag-warscheid/autoprot)).
  - All analyses in this repository were performed with autoprot and cannot be run without it.
- Installation time largely depends on the time required to compile the R packages.
  - With a fast internet connection, the installation on a standard desktop computer should take less than 30 minutes.
- No non-standard libraries or hardware are required to run the scripts

## How to run
- Save and extract the 'txt', 'results' and 'marker_list' folder
- With autoprot installed, run the jupyter notebook 'Tb_PMP_script_data_processing.ipynb'

## How to get help
If something does not work as expected, please reach out to us via the GitHub issues function.
