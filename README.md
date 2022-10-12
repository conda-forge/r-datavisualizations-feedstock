About r-datavisualizations
==========================

Home: http://www.deepbionics.org

Package license: GPL-3.0-only

Feedstock license: [BSD-3-Clause](https://github.com/conda-forge/r-datavisualizations-feedstock/blob/main/LICENSE.txt)

Summary: Gives access to data visualisation methods that are relevant from the data scientist's point of view. The flagship idea of 'DataVisualizations' is the mirrored density plot (MD-plot) for either classified or non-classified multivariate data published in Thrun, M.C. et al.: "Analyzing the Fine Structure of Distributions" (2020), PLoS ONE, <DOI:10.1371/journal.pone.0238835>. The MD-plot outperforms the box-and-whisker diagram (box plot), violin plot and bean plot and geom_violin plot of ggplot2. Furthermore, a collection of various visualization methods for univariate data is provided. In the case of exploratory data analysis, 'DataVisualizations' makes it possible to inspect the distribution of each feature of a dataset visually through a combination of four methods. One of these methods is the Pareto density estimation (PDE) of the probability density function (pdf). Additionally, visualizations of the distribution of distances using PDE, the scatter-density plot using PDE for two variables as well as the Shepard density plot and the Bland-Altman plot are presented here. Pertaining to classified high-dimensional data, a number of visualizations are described, such as f.ex. the heat map and silhouette plot. A political map of the world or Germany can be visualized with the additional information defined by a classification of countries or regions. By extending the political map further, an uncomplicated function for a Choropleth map can be used which is useful for measurements across a geographic area. For categorical features, the Pie charts, slope charts and fan plots, improved by the ABC analysis, become usable. More detailed explanations are found in the book by Thrun, M.C.: "Projection-Based Clustering through Self-Organization and Swarm Intelligence" (2018) <DOI:10.1007/978-3-658-20540-9>.

Current build status
====================


<table>
    
  <tr>
    <td>Azure</td>
    <td>
      <details>
        <summary>
          <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=12937&branchName=main">
            <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/r-datavisualizations-feedstock?branchName=main">
          </a>
        </summary>
        <table>
          <thead><tr><th>Variant</th><th>Status</th></tr></thead>
          <tbody><tr>
              <td>linux_64_r_base4.1</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=12937&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/r-datavisualizations-feedstock?branchName=main&jobName=linux&configuration=linux_64_r_base4.1" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_64_r_base4.2</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=12937&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/r-datavisualizations-feedstock?branchName=main&jobName=linux&configuration=linux_64_r_base4.2" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_64_r_base4.1</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=12937&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/r-datavisualizations-feedstock?branchName=main&jobName=osx&configuration=osx_64_r_base4.1" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_64_r_base4.2</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=12937&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/r-datavisualizations-feedstock?branchName=main&jobName=osx&configuration=osx_64_r_base4.2" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>win_64</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=12937&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/r-datavisualizations-feedstock?branchName=main&jobName=win&configuration=win_64_" alt="variant">
                </a>
              </td>
            </tr>
          </tbody>
        </table>
      </details>
    </td>
  </tr>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-r--datavisualizations-green.svg)](https://anaconda.org/conda-forge/r-datavisualizations) | [![Conda Downloads](https://img.shields.io/conda/dn/conda-forge/r-datavisualizations.svg)](https://anaconda.org/conda-forge/r-datavisualizations) | [![Conda Version](https://img.shields.io/conda/vn/conda-forge/r-datavisualizations.svg)](https://anaconda.org/conda-forge/r-datavisualizations) | [![Conda Platforms](https://img.shields.io/conda/pn/conda-forge/r-datavisualizations.svg)](https://anaconda.org/conda-forge/r-datavisualizations) |

Installing r-datavisualizations
===============================

Installing `r-datavisualizations` from the `conda-forge` channel can be achieved by adding `conda-forge` to your channels with:

```
conda config --add channels conda-forge
conda config --set channel_priority strict
```

Once the `conda-forge` channel has been enabled, `r-datavisualizations` can be installed with `conda`:

```
conda install r-datavisualizations
```

or with `mamba`:

```
mamba install r-datavisualizations
```

It is possible to list all of the versions of `r-datavisualizations` available on your platform with `conda`:

```
conda search r-datavisualizations --channel conda-forge
```

or with `mamba`:

```
mamba search r-datavisualizations --channel conda-forge
```

Alternatively, `mamba repoquery` may provide more information:

```
# Search all versions available on your platform:
mamba repoquery search r-datavisualizations --channel conda-forge

# List packages depending on `r-datavisualizations`:
mamba repoquery whoneeds r-datavisualizations --channel conda-forge

# List dependencies of `r-datavisualizations`:
mamba repoquery depends r-datavisualizations --channel conda-forge
```


About conda-forge
=================

[![Powered by
NumFOCUS](https://img.shields.io/badge/powered%20by-NumFOCUS-orange.svg?style=flat&colorA=E1523D&colorB=007D8A)](https://numfocus.org)

conda-forge is a community-led conda channel of installable packages.
In order to provide high-quality builds, the process has been automated into the
conda-forge GitHub organization. The conda-forge organization contains one repository
for each of the installable packages. Such a repository is known as a *feedstock*.

A feedstock is made up of a conda recipe (the instructions on what and how to build
the package) and the necessary configurations for automatic building using freely
available continuous integration services. Thanks to the awesome service provided by
[Azure](https://azure.microsoft.com/en-us/services/devops/), [GitHub](https://github.com/),
[CircleCI](https://circleci.com/), [AppVeyor](https://www.appveyor.com/),
[Drone](https://cloud.drone.io/welcome), and [TravisCI](https://travis-ci.com/)
it is possible to build and upload installable packages to the
[conda-forge](https://anaconda.org/conda-forge) [Anaconda-Cloud](https://anaconda.org/)
channel for Linux, Windows and OSX respectively.

To manage the continuous integration and simplify feedstock maintenance
[conda-smithy](https://github.com/conda-forge/conda-smithy) has been developed.
Using the ``conda-forge.yml`` within this repository, it is possible to re-render all of
this feedstock's supporting files (e.g. the CI configuration files) with ``conda smithy rerender``.

For more information please check the [conda-forge documentation](https://conda-forge.org/docs/).

Terminology
===========

**feedstock** - the conda recipe (raw material), supporting scripts and CI configuration.

**conda-smithy** - the tool which helps orchestrate the feedstock.
                   Its primary use is in the construction of the CI ``.yml`` files
                   and simplify the management of *many* feedstocks.

**conda-forge** - the place where the feedstock and smithy live and work to
                  produce the finished article (built conda distributions)


Updating r-datavisualizations-feedstock
=======================================

If you would like to improve the r-datavisualizations recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`conda-forge` channel, whereupon the built conda packages will be available for
everybody to install and use from the `conda-forge` channel.
Note that all branches in the conda-forge/r-datavisualizations-feedstock are
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

* [@conda-forge/r](https://github.com/conda-forge/r/)

