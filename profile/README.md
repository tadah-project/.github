# Tadah!

Tadah! is a C++ toolkit for developing machine-learning interatomic
potentials and running them in LAMMPS.

**Documentation:** <https://tadah.readthedocs.io>

## Start here

| Repository | What it is |
|---|---|
| [tadah.mlip](https://github.com/tadah-project/tadah.mlip) | The `tadah` program (training, prediction, data tools, hyperparameter optimisation) and the documentation. |
| [tadah.lammps](https://github.com/tadah-project/tadah.lammps) | `pair_style tadah`, the plugin that runs Tadah! potentials in LAMMPS. |

## Components

The build fetches these libraries automatically. They have no issue
trackers of their own.

| Repository | What it is |
|---|---|
| [core](https://github.com/tadah-project/core) | Configuration, key registry and shared types |
| [models](https://github.com/tadah-project/models) | Descriptors, cutoffs and regressors |
| [mlip](https://github.com/tadah-project/mlip) | Training and prediction engines |
| [md](https://github.com/tadah-project/md) | Molecular-dynamics evaluation layer |
| [hpo](https://github.com/tadah-project/hpo) | Hyperparameter-optimisation engine |
| [cmake-tools](https://github.com/tadah-project/cmake-tools) | Shared CMake helpers |

## Citing Tadah!

M. Kirsz, A. Daramola, A. Hermann, H. Zong, G. J. Ackland,
*Tadah! a Swiss army knife for developing and deployment of machine
learning interatomic potentials*, Computer Physics Communications **315**,
109701 (2025), [doi:10.1016/j.cpc.2025.109701](https://doi.org/10.1016/j.cpc.2025.109701).
