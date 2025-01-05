# An Actually Reproducible Simulation Study in RStudio
By: Jasmijn Bazen
Date of creation: 08/11/2024

Purpose: To show what an actual nicely reproducible simulation study entails. So no changing code to specify working directory, no downloading of extra files etc. 

Software versions: 
General:
R version 4.3.2 (2023-10-31 ucrt)
Platform: x86_64-w64-mingw32/x64 (64-bit)
Running under: Windows 11 x64 (build 22631)
R Packages:
tidyverse_2.0.0
mice_3.16.0
Hmisc_5.1-1 


# The folder structure

Compendium/
├── data
│   ├── BMX_I.XPT
│   ├── BPX_I.XPT
│   ├── DEMO_I.XPT
│   ├── GHB_I.XPT
│   └── TCHOL_XPT
├── docs
│   └── references.bib
├── results
│   └── Figure_STRATOS
├── scripts
│   └── R_code_reprodicibilty.qmd
├── LICENSE.md
├── R_project_reproducibility.Rproj
└── README.md

All data, the references.bib, the LICENSE.md, the R_project_reproducibility.Rproj and the README.md are read only.
The code is human-generated.
The figure in the results folder is project-generated. 


How to use:
Start up the R_project_reproducibility.Rproj file in RStudio. Open the R_code_reprodicibilty.qmd file in this project space. You can now run the code in the .qmd file and reproduce the research! 






