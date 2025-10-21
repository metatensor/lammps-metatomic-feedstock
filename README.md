About lammps-metatomic-feedstock
================================

Feedstock license: [BSD-3-Clause](https://github.com/metatensor/lammps-metatomic-feedstock/blob/main/LICENSE.txt)

Home: https://docs.metatensor.org/metatomic/latest/engines/lammps.html

Package license: GPL-2.0-only

Summary: Metatomic-enabled version of LAMMPS

Development: https://github.com/metatensor/lammps

Documentation: https://docs.metatensor.org/metatomic/latest/engines/lammps.html

Metatomic-enabled version of LAMMPS

Current build status
====================


<table>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-lammps--metatomic-green.svg)](https://anaconda.org/metatensor/lammps-metatomic) | [![Conda Downloads](https://img.shields.io/conda/dn/metatensor/lammps-metatomic.svg)](https://anaconda.org/metatensor/lammps-metatomic) | [![Conda Version](https://img.shields.io/conda/vn/metatensor/lammps-metatomic.svg)](https://anaconda.org/metatensor/lammps-metatomic) | [![Conda Platforms](https://img.shields.io/conda/pn/metatensor/lammps-metatomic.svg)](https://anaconda.org/metatensor/lammps-metatomic) |

Installing lammps-metatomic
===========================

Installing `lammps-metatomic` from the `metatensor` channel can be achieved by adding `metatensor` to your channels with:

```
conda config --add channels metatensor
conda config --set channel_priority strict
```

Once the `metatensor` channel has been enabled, `lammps-metatomic` can be installed with `conda`:

```
conda install lammps-metatomic
```

or with `mamba`:

```
mamba install lammps-metatomic
```

It is possible to list all of the versions of `lammps-metatomic` available on your platform with `conda`:

```
conda search lammps-metatomic --channel metatensor
```

or with `mamba`:

```
mamba search lammps-metatomic --channel metatensor
```

Alternatively, `mamba repoquery` may provide more information:

```
# Search all versions available on your platform:
mamba repoquery search lammps-metatomic --channel metatensor

# List packages depending on `lammps-metatomic`:
mamba repoquery whoneeds lammps-metatomic --channel metatensor

# List dependencies of `lammps-metatomic`:
mamba repoquery depends lammps-metatomic --channel metatensor
```




Updating lammps-metatomic-feedstock
===================================

If you would like to improve the lammps-metatomic recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`metatensor` channel, whereupon the built conda packages will be available for
everybody to install and use from the `metatensor` channel.
Note that all branches in the metatensor/lammps-metatomic-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks, and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](https://docs.conda.io/projects/conda-build/en/latest/resources/define-metadata.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](https://docs.conda.io/projects/conda-build/en/latest/resources/define-metadata.html#build-number-and-string)
   back to 0.

Feedstock Maintainers
=====================

* [@Luthaf](https://github.com/Luthaf/)
* [@abmazitov](https://github.com/abmazitov/)

