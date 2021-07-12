---
layout: default
---

## QM9NMR dataset

 
### Supplementary data for

_Revving up 13C NMR shielding predictions across chemical space: benchmarks for atoms-in-molecules kernel machine learning with new data for 134 kilo molecules_  
Amit Gupta, Sabyasachi Chakraborty and Raghunathan Ramakrishnan     
Mach. Learn.: Sci. Technol. 2 (2021) 035010     
[https://doi.org/10.1088/2632-2153/abe347](https://doi.org/10.1088/2632-2153/abe347)

```
@article{gupta2021revving,
  title={Revving up 13C NMR shielding predictions across chemical space: Benchmarks for atoms-in-molecules kernel machine learning with new data for 134 kilo molecules},
  author={Gupta, Amit and Chakraborty, Sabyasachi and Ramakrishnan, Raghunathan},
  journal={Machine Learning: Science and Technology},
  volume={2},
  number={3},
  pages={035010},
  year={2021},
  publisher={IOP Publishing}
}
```

```
Last modified: 21 July 2021

SI_baseline_geo.xyz ⟶ Contains 130,831 molecules relaxed at PM7 level.

Revision notes:       In our original upload, the atomic indices of the baseline data such as the PM7 geometries were shuffled. We thank Eric Collins for pointing this out. We have now uploaded the file 'pm7.tar.gz' with correct atomic indices.

SI_DFT_geo.xyz ⟶ Contains 130,831 molecules relaxed at B3LYP/6-31G(2df,p) level.

SI_DFT_NMR.txt ⟶ For each molecule in SI_DFT_geo.xyz, file contains number of atoms, followed by molecule name and isotropic shielding tensors per atom in the molecule in Gas, CCl4, THF, Acetone, Methanol and DMSO respectively, obtained at mPW1PW91/6-311+G(2d,p).
SI_baseline_NMR.txt ⟶ For each molecule in SI_baseline_geo.xyz, file contains number of atoms, followed by molecule name and isotropic shielding tensors per atom in the molecule in Gas phase obtained at B3LYP/sto-3g level.

Structure Files
File	Comments
SI_12Drugs_DFT_geo.xyz	Contains 12 Drug molecules relaxed at B3LYP/6-31G(2df,p) level.
SI_12Drugs_baseline_geo.xyz	Contains 12 Drug molecules relaxed at PM7 level.
SI_40Drugs_DFT_geo.xyz	Contains 40 Drug molecules relaxed at B3LYP/6-31G(2df,p) level.
SI_40Drugs_baseline_geo.xyz	Contains 40 Drug molecules relaxed at PM7 level.
SI_PAH_DFT_geo.xyz	Contains 5 Polycyclic Aromatic Hydrocarbons molecules relaxed at B3LYP/6-31G(2df,p) level.
SI_PAH_baseline_geo.xyz	Contains 5 Polycyclic Aromatic Hydrocarbons molecules relaxed at PM7 level.
SI_GDB10to17_DFT_geo.xyz	Contains 200 molecules from GDB10 to GDB17 molecules relaxed at B3LYP/6-31G(2df,p) level.
SI_GDB10to17_baseline_geo.xyz	Contains 200 molecules from GDB10 to GDB17 molecules relaxed at PM7 level.

Data Files
File	Comments
SI_12Drugs_DFT_NMR.txt	For each molecule in SI_12Drugs_DFT_geo.xyz, file contains number of atoms, molecule name and isotropic shielding tensors per atom, in Gas phase at mPW1PW91/6-311+G(2d,p).
SI_12Drugs_baseline_NMR.txt	For each molecule in SI_12Drugs_baseline_geo.xyz, file contains number of atoms, molecule name and isotropic shielding tensors per atom, in Gas phase at B3LYP/sto-3g level.
SI_40Drugs_DFT_NMR.txt	For each molecule in SI_40Drugs_DFT_geo.xyz, file contains number of atoms, molecule name and isotropic shielding tensors per atom, in Gas phase at mPW1PW91/6-311+G(2d,p).
SI_40Drugs_baseline_NMR.txt	For each molecule in SI_40Drugs_baseline_geo.xyz, file contains number of atoms, molecule name and isotropic shielding tensors per atom, in Gas phase at B3LYP/sto-3g level.
SI_PAH_DFT_NMR.txt	For each molecule in SI_PAH_DFT_geo.xyz, file contains number of atoms, molecule name and isotropic shielding tensors per atom, in Gas phase at mPW1PW91/6-311+G(2d,p).
SI_PAH_baseline_NMR.txt	For each molecule in SI_PAH_baseline_geo.xyz, file contains number of atoms, molecule name and isotropic shielding tensors per atom, in Gas phase at B3LYP/sto-3g level.
SI_GDB10to17_DFT_NMR.txt	For each molecule in SI_GDB10to17_DFT_geo.xyz, file contains number of atoms, molecule name and isotropic shielding tensors per atom, in Gas phase at mPW1PW91/6-311+G(2d,p).
SI_GDB10to17_baseline_NMR.txt	For each molecule in SI_GDB10to17_baseline_geo.xyz, file contains number of atoms, molecule name and isotropic shielding tensors per atom, in Gas phase at B3LYP/sto-3g level.

13C shielding of the reference compound tetramethylsilane (TMS) [in ppm]
Gas - 186.9704
CCl4 - 187.2352
THF - 187.4958
Acetone - 187.594875
Methanol - 187.6181
DMSO - 187.6304
```

