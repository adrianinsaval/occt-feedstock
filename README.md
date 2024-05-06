About occt-feedstock
====================

Feedstock license: [BSD-3-Clause](https://github.com/conda-forge/occt-feedstock/blob/main/LICENSE.txt)

Home: https://www.opencascade.com/

Package license: LGPL-2.1-only

Summary: this is the occ (opencascade) CAD-Kernel

Development: http://git.dev.opencascade.org/gitweb/?p=occt.git

Documentation: https://www.opencascade.com/content/documentation

Open Cascade Technology (OCCT), formerly called CAS.CADE
is an open source software development platform for 3D CAD,
CAM, CAE, etc. that is developed and supported by Open Cascade SAS.


Current build status
====================


<table>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-occt-green.svg)](https://anaconda.org/freecad/occt) | [![Conda Downloads](https://img.shields.io/conda/dn/freecad/occt.svg)](https://anaconda.org/freecad/occt) | [![Conda Version](https://img.shields.io/conda/vn/freecad/occt.svg)](https://anaconda.org/freecad/occt) | [![Conda Platforms](https://img.shields.io/conda/pn/freecad/occt.svg)](https://anaconda.org/freecad/occt) |

Installing occt
===============

Installing `occt` from the `freecad/label/dev` channel can be achieved by adding `freecad/label/dev` to your channels with:

```
conda config --add channels freecad/label/dev
conda config --set channel_priority strict
```

Once the `freecad/label/dev` channel has been enabled, `occt` can be installed with `conda`:

```
conda install occt
```

or with `mamba`:

```
mamba install occt
```

It is possible to list all of the versions of `occt` available on your platform with `conda`:

```
conda search occt --channel freecad/label/dev
```

or with `mamba`:

```
mamba search occt --channel freecad/label/dev
```

Alternatively, `mamba repoquery` may provide more information:

```
# Search all versions available on your platform:
mamba repoquery search occt --channel freecad/label/dev

# List packages depending on `occt`:
mamba repoquery whoneeds occt --channel freecad/label/dev

# List dependencies of `occt`:
mamba repoquery depends occt --channel freecad/label/dev
```




Updating occt-feedstock
=======================

If you would like to improve the occt recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`freecad` channel, whereupon the built conda packages will be available for
everybody to install and use from the `freecad` channel.
Note that all branches in the conda-forge/occt-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](https://docs.conda.io/projects/conda-build/en/latest/resources/define-metadata.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](https://docs.conda.io/projects/conda-build/en/latest/resources/define-metadata.html#build-number-and-string)
   back to 0.

Feedstock Maintainers
=====================

* [@adrianinsaval](https://github.com/adrianinsaval/)
* [@looooo](https://github.com/looooo/)

