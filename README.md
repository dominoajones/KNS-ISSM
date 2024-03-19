# KNS-ISSM
Using Ice-sheet and Sea-level System Model (ISSM) to model Kangiata Nunaata Sermia (KNS; SW Greenland) over the last 1000 years.

ISSM is a framework for modeling ice flow on ice sheet/ice shelf systems using Finite Element Analysis. Version 4.19 of ISSM is open-source and publicly available at https://issm.jpl.nasa.gov/.

This project is undertaken by Mx. Domino Jones (PhD student) at the University of Liverpool, supervised by Prof. Doug Mair, Prof. James Lea, and Dr. Isabel Nias. 
Contact: Domino.Jones@liverpool.ac.uk

Structure of repo:
- **source-code** holds ISSM pre-compiled binaries
- **tinkering** contains .m scripts under development.
- **trunk** holds datasets (for velocity, topography, SMB, and temperature) and .shp files for KNS system domain.
- **KNS-setup** contains .exp files of KNS system domain and miscellanous .m scripts.
-  **run** contains files related to simulation runs.
- **figs** holds key figure outputs from simulation runs.

More information about datasets (references and pre-processing procedures) can be found on the readme.txt in the **trunk** folder.
