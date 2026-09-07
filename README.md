About mitmproxy-rs-feedstock
============================

Feedstock license: [BSD-3-Clause](https://github.com/conda-forge/mitmproxy-rs-feedstock/blob/main/LICENSE.txt)

Home: https://github.com/mitmproxy/mitmproxy_rs

Package license: MIT

Summary: This package contains mitmproxy's Rust bits.

Development: https://github.com/mitmproxy/mitmproxy-rs

# mitmproxy_rs

This package contains mitmproxy's Rust bits.

[![dev documentation](https://shields.mitmproxy.org/badge/docs-Python%20API-blue.svg)](https://mitmproxy.github.io/mitmproxy_rs/)

https://github.com/mitmproxy/mitmproxy_rs

Current build status
====================


<table><tr>
    <td>GitHub Actions</td>
    <td>
      <a href="https://github.com/conda-forge/mitmproxy-rs-feedstock/actions/workflows/conda-build.yml">
        <img src="https://github.com/conda-forge/mitmproxy-rs-feedstock/actions/workflows/conda-build.yml/badge.svg?event=push&branch=main">
      </a>
    </td>
  </tr>
    
  <tr>
    <td>Azure</td>
    <td>
      <details>
        <summary>
          <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=26960&branchName=main">
            <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/mitmproxy-rs-feedstock?branchName=main">
          </a>
        </summary>
        <table>
          <thead><tr><th>Variant</th><th>Status</th></tr></thead>
          <tbody><tr>
              <td>osx_64_python3.12.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=26960&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/mitmproxy-rs-feedstock?branchName=main&jobName=osx&configuration=osx%20osx_64_python3.12.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_64_python3.13.____cp313</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=26960&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/mitmproxy-rs-feedstock?branchName=main&jobName=osx&configuration=osx%20osx_64_python3.13.____cp313" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_64_python3.14.____cp314</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=26960&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/mitmproxy-rs-feedstock?branchName=main&jobName=osx&configuration=osx%20osx_64_python3.14.____cp314" alt="variant">
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
| [![Conda Recipe](https://img.shields.io/badge/recipe-mitmproxy--linux-green.svg)](https://anaconda.org/conda-forge/mitmproxy-linux) | [![Conda Downloads](https://img.shields.io/conda/dn/conda-forge/mitmproxy-linux.svg)](https://anaconda.org/conda-forge/mitmproxy-linux) | [![Conda Version](https://img.shields.io/conda/vn/conda-forge/mitmproxy-linux.svg)](https://anaconda.org/conda-forge/mitmproxy-linux) | [![Conda Platforms](https://img.shields.io/conda/pn/conda-forge/mitmproxy-linux.svg)](https://anaconda.org/conda-forge/mitmproxy-linux) |
| [![Conda Recipe](https://img.shields.io/badge/recipe-mitmproxy--macos-green.svg)](https://anaconda.org/conda-forge/mitmproxy-macos) | [![Conda Downloads](https://img.shields.io/conda/dn/conda-forge/mitmproxy-macos.svg)](https://anaconda.org/conda-forge/mitmproxy-macos) | [![Conda Version](https://img.shields.io/conda/vn/conda-forge/mitmproxy-macos.svg)](https://anaconda.org/conda-forge/mitmproxy-macos) | [![Conda Platforms](https://img.shields.io/conda/pn/conda-forge/mitmproxy-macos.svg)](https://anaconda.org/conda-forge/mitmproxy-macos) |
| [![Conda Recipe](https://img.shields.io/badge/recipe-mitmproxy--rs-green.svg)](https://anaconda.org/conda-forge/mitmproxy-rs) | [![Conda Downloads](https://img.shields.io/conda/dn/conda-forge/mitmproxy-rs.svg)](https://anaconda.org/conda-forge/mitmproxy-rs) | [![Conda Version](https://img.shields.io/conda/vn/conda-forge/mitmproxy-rs.svg)](https://anaconda.org/conda-forge/mitmproxy-rs) | [![Conda Platforms](https://img.shields.io/conda/pn/conda-forge/mitmproxy-rs.svg)](https://anaconda.org/conda-forge/mitmproxy-rs) |
| [![Conda Recipe](https://img.shields.io/badge/recipe-mitmproxy--windows-green.svg)](https://anaconda.org/conda-forge/mitmproxy-windows) | [![Conda Downloads](https://img.shields.io/conda/dn/conda-forge/mitmproxy-windows.svg)](https://anaconda.org/conda-forge/mitmproxy-windows) | [![Conda Version](https://img.shields.io/conda/vn/conda-forge/mitmproxy-windows.svg)](https://anaconda.org/conda-forge/mitmproxy-windows) | [![Conda Platforms](https://img.shields.io/conda/pn/conda-forge/mitmproxy-windows.svg)](https://anaconda.org/conda-forge/mitmproxy-windows) |

Installing mitmproxy-rs
=======================

Installing `mitmproxy-rs` from the `conda-forge` channel can be achieved by adding `conda-forge` to your channels with:

```
conda config --add channels conda-forge
conda config --set channel_priority strict
```

How to use
----------

<details>
<summary>With conda</summary>

```
conda install mitmproxy-linux mitmproxy-macos mitmproxy-rs mitmproxy-windows
```

</details>

<details>
<summary>With mamba</summary>

```
mamba install mitmproxy-linux mitmproxy-macos mitmproxy-rs mitmproxy-windows
```

</details>

<details>
<summary>With pixi</summary>

```
# for adding to your local project
pixi add mitmproxy-linux mitmproxy-macos mitmproxy-rs mitmproxy-windows
# for installing globally
pixi global install mitmproxy-linux mitmproxy-macos mitmproxy-rs mitmproxy-windows
```

</details>

Search package versions
-----------------------

It is possible to list all of the versions of `mitmproxy-linux` available on your platform:

<details>
<summary>With conda</summary>

```
conda search mitmproxy-linux --channel conda-forge
```

</details>

<details>
<summary>With mamba</summary>

```
mamba search mitmproxy-linux --channel conda-forge
```

</details>

<details>
<summary>With pixi</summary>

```
pixi search mitmproxy-linux --channel conda-forge
```

</details>

<details>
<summary>With mamba repoquery, which may provide more information</summary>

```
# Search all versions available on your platform:
mamba repoquery search mitmproxy-linux --channel conda-forge

# List packages depending on `mitmproxy-linux`:
mamba repoquery whoneeds mitmproxy-linux --channel conda-forge

# List dependencies of `mitmproxy-linux`:
mamba repoquery depends mitmproxy-linux --channel conda-forge
```

</details>


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
[conda-forge](https://anaconda.org/conda-forge) [anaconda.org](https://anaconda.org/)
channel for Linux, Windows and OSX respectively.

To manage the continuous integration and simplify feedstock maintenance,
[conda-smithy](https://github.com/conda-forge/conda-smithy) has been developed.
Using the ``conda-forge.yml`` within this repository, it is possible to re-render all of
this feedstock's supporting files (e.g. the CI configuration files) with ``conda smithy rerender``.

For more information, please check the [conda-forge documentation](https://conda-forge.org/docs/).

Terminology
===========

**feedstock** - the conda recipe (raw material), supporting scripts and CI configuration.

**conda-smithy** - the tool which helps orchestrate the feedstock.
                   Its primary use is in the construction of the CI ``.yml`` files
                   and simplify the management of *many* feedstocks.

**conda-forge** - the place where the feedstock and smithy live and work to
                  produce the finished article (built conda distributions)


Updating mitmproxy-rs-feedstock
===============================

If you would like to improve the mitmproxy-rs recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`conda-forge` channel, whereupon the built conda packages will be available for
everybody to install and use from the `conda-forge` channel.
Note that all branches in the conda-forge/mitmproxy-rs-feedstock are
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

* [@moritzwilksch](https://github.com/moritzwilksch/)
* [@ytausch](https://github.com/ytausch/)

