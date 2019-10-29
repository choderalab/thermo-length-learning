thermo-length-learning
==============================

Machine learning of thermodynamic lengths.

### Contains

Dataset of relative hydration free energies and variances for pairs of molecules in the freesolv[Freesolv](https://github.com/MobleyLab/FreeSolv) dataset, for pairs of molecules with (0 or 1 unique old heavy atoms) and (0 or 1 unique new heavy atoms).

`generate-pairs.ipynb` searches through freesolv to find appropriate pairs, and analysis is performed in `analysis.ipynb`.

The intention is that it may be possible to _learn_ the variance of a simulation _a priori_ and use this for intelligent experiment design, using software such as [DiffNet](https://github.com/forcefield/DiffNet). 

### Useful References

(1) Mobley, D. L., and Guthrie, J. P., "FreeSolv: A database of experimental and calculated hydration free energies, with input files", Journal of Computer-Aided Molecular Design, 28(7):711-720 (2014) [Publication](https://pubs.acs.org/doi/abs/10.1021/ct800409d).

(2) Huafeng Xu, Optimal measurement network of pairwise differences, (2019). [Preprint](https://arxiv.org/abs/1906.08599).

### Copyright

Copyright (c) 2019, Chodera lab

