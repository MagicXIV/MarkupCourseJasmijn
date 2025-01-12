# A Reproducible First Analysis of PISA Data in RStudio
By: Jasmijn Bazen
Date of creation: 10/01/2025

Purpose: TO have a fully reproducible study on a subset of the PISA dataset. No changing code to specify working directory, no downloading of extra files. Possibly needing to run the last 3 lines of code in the console instead due to the package being used. 

Software versions: 
General:
R version 4.3.2 (2023-10-31 ucrt)
Platform: x86_64-w64-mingw32/x64 (64-bit)
Running under: Windows 11 x64 (build 22631)
R Packages:
tidyverse_2.0.0
haven_2.5.4
dplyr_1.1.4
tidyr_1.3.1
lavaan_0.6.19
lavaanPlot_0.8.1
shiny_1.8.1.1
ggplot2_3.4.4
devtools_2.4.5
saveLavaanPlot_0.2.2
saveLavaanPlot_0.3.0


# The folder structure

01_research_compendium/
├── data
│   └── pisa18_m.RDS
├── docs
│   └── references.bib
├── results
│   ├── DistrMissingPerCountry.tif
│   ├── EmptySEMModel.png
│   ├── ItemEasinessVsMissingValues.tif
│   ├── SEMModelDE.png
│   └── SEMModelNL.png
├── scripts
│   └── R_code_FirstAnalysis_PISAData.qmd
├── 01_research_compendium.Rproj
├── LICENSE.md
└── README.md

The data, the references.bib, the LICENSE.md, the R_code_FirstAnalysis_PISAData.qmd and the README.md are read only.
The code is human-generated.
The figures in the results folder are project-generated. 


How to use:
Start up the R_code_FirstAnalysis_PISAData.Rproj file in RStudio. Open the R_code_FirstAnalysis_PISAData.qmd file from the scripts folder in this project space. You can now run the code in the .qmd file and reproduce the research! 
If the last 3 lines of code do not work. Please try running them directly in the console, it should work then. 
