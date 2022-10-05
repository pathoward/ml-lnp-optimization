# ml-lnp-optimization
## Patrick Howard, August 2022
## Mirkin Group, Department of Chemistry, Northwestern University

An in-progress program leveraging `sklearn` to suggest a four-component formulation to produce an mRNA-containing lipid nanoparticle (LNP) of a specific diameter.

### Vision
Code will perform 2 functions: add/edit formulations and resulting particle size based on formulation number, and return ideal formulation based on inputted material constraints and desired size

### Acknowledgements
Data:
Andrew J. Sinegra, Michael Evangelopoulos, Jungsoo Park, Ziyin Huang, and Chad A. Mirkin. *Nano Letters* **2021** *21* (15), 6584-6591
DOI: 10.1021/acs.nanolett.1c01973

ML Package:
Scikit-learn: Machine Learning in Python, Pedregosa et al., *JMLR 12*, pp. 2825-2830, **2011**

### Reagent Key for cleaned CSV

**Libraries:**
- 10** = A_ 
- 20** = B_
- 30** = C_

**Phospholipids:**
- 1 = DOPC
- 2 = DSPC
- 3 = DOPE

**Ionizable Lipid:**
- 1 = DLin-MC3
- 2 = 18:1 DAP

**Lipid PEG:**
- 1 = C14
- 2 = C16
- 3 = C18

**Surface DNA:**
- 1 = T21
- 2 = GGT7
