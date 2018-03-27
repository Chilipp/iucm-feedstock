About iucm
==========

Home: https://github.com/Chilipp/iucm

Package license: GPLv3

Feedstock license: BSD 3-Clause

Summary: An Integrated Urban Complexity Model

This model simulates urban growth and transformation with the objective of
minimising the energy required for transportation.


Current build status
====================

Linux, OSX: [![TravisCI](https://travis-ci.org/Chilipp/iucm-feedstock.svg?branch=master)](https://travis-ci.org/chilipp/iucm-feedstock)
Windows: [![AppVeyor](https://ci.appveyor.com/api/projects/status/github/chilipp/iucm-feedstock?svg=True)](https://ci.appveyor.com/project/chilipp/iucm-feedstock/branch/master)

Current release info
====================
Version: [![Anaconda-Server Badge](https://anaconda.org/chilipp/iucm/badges/version.svg)](https://anaconda.org/chilipp/iucm)
Downloads: [![Anaconda-Server Badge](https://anaconda.org/chilipp/iucm/badges/downloads.svg)](https://anaconda.org/chilipp/iucm)

Installing iucm
=================

Installing `iucm` from the `chilipp` channel can be achieved by adding `chilipp` to your channels with:

```
conda config --add channels chilipp
```

Once the `chilipp` channel has been enabled, `iucm` can be installed with:

```
conda install iucm
```

It is possible to list all of the versions of `iucm` available on your platform with:

```
conda search iucm --channel chilipp
```


About this repository
=====================

This repository is motivated by the conda-forge channel to build the iucm
package for the different platforms. It is based on the
[docrep-feedstock](https://github.com/conda-forge/docrep-feedstock)
from March, 27th, 2018.

This repository will be removed as soon as the package is added to the
conda-forge channel.


Terminology
===========

**feedstock** - the conda recipe (raw material), supporting scripts and CI configuration.

**conda-smithy** - the tool which helps orchestrate the feedstock.
                   Its primary use is in the construction of the CI ``.yml`` files
                   and simplify the management of *many* feedstocks.
