# Tadah!

Machine-learning interatomic potentials, with a LAMMPS plugin.
Documentation: <https://tadah.readthedocs.io>

**Start here**

- [tadah.mlip](https://github.com/tadah-project/tadah.mlip): the `tadah`
  program (training, prediction, hyperparameter optimisation) and the
  documentation.
- [tadah.lammps](https://github.com/tadah-project/tadah.lammps): the
  `pair_style tadah` plugin for LAMMPS.

**Components** (fetched by the build automatically)

- [core](https://github.com/tadah-project/core): configuration and shared types
- [models](https://github.com/tadah-project/models): descriptors, cutoffs and regressors
- [mlip](https://github.com/tadah-project/mlip): the training engine
- [md](https://github.com/tadah-project/md): molecular-dynamics drivers
- [hpo](https://github.com/tadah-project/hpo): hyperparameter optimisation
- [cmake-tools](https://github.com/tadah-project/cmake-tools): shared CMake helpers
