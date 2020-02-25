# AlorsBot - Adaptive Locomotion Robotic System

## Introduction

This repository contains the parts designed for the AlorsBot.



## Folder Hierarchy

```bash
.
├── 3D_Prints
│   └── 3D_Prints_Records.xlsx
├── inventor
│   ├── assemblies
│   │   └── wheelAssembly.iam
│   ├── excel
│   │   └── wheelParameters.xlsx
│   │── extras
│   │── wheel.ipj
│   │── README.md
│   └── parts
│        ├── printPrototypes
│        │   └── *.ipt
│        │── *.ipt
│        └── README.md
├── stl 
│   ├── prototypes
│   │   └── *.stl
│   └── *.stl
└── README.md
```
- `3D_Prints` directory contains an excel sheet which contains records of the 3D prints made.
- `stl` directory contains the stl files associated with each of the inventor files `fileName.ipt` for viewing purposes.
- `inventor` directory contains the designed parts and their associated files.
    - `excel` is where `wheelParameters.xlsx` can be found. This document contains all the parameters used for parts located in `inventor\parts\wheel\` directory. 
    - Once a parameter value has been modified and saved, the part files and the assembly can be updated to reflect those changes by simply refreshing. 
