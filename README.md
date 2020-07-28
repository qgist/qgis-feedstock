About qgis
==========

Home: http://qgis.org/

Package license: GPL-2.0

Feedstock license: BSD-3-Clause

Summary: A free and open source Geographic Information System (GIS).

QGIS is a user friendly Open Source Geographic Information System (GIS)
licensed under the GNU General Public License. QGIS is an official
project of the Open Source Geospatial Foundation (OSGeo). It runs on
Linux, Unix, Mac OSX, Windows and Android and supports numerous vector,
raster, and database formats and functionalities.


Current build status
====================


<table>
    
  <tr>
    <td>Azure</td>
    <td>
      <details>
        <summary>
          <a href="https://dev.azure.com/qgist/feedstock-builds/_build/latest?definitionId=1&branchName=master">
            <img src="https://dev.azure.com/qgist/feedstock-builds/_apis/build/status/qgis-feedstock?branchName=master">
          </a>
        </summary>
        <table>
          <thead><tr><th>Variant</th><th>Status</th></tr></thead>
          <tbody><tr>
              <td>linux_python3.6.____cpython</td>
              <td>
                <a href="https://dev.azure.com/qgist/feedstock-builds/_build/latest?definitionId=1&branchName=master">
                  <img src="https://dev.azure.com/qgist/feedstock-builds/_apis/build/status/qgis-feedstock?branchName=master&jobName=linux&configuration=linux_python3.6.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_python3.7.____cpython</td>
              <td>
                <a href="https://dev.azure.com/qgist/feedstock-builds/_build/latest?definitionId=1&branchName=master">
                  <img src="https://dev.azure.com/qgist/feedstock-builds/_apis/build/status/qgis-feedstock?branchName=master&jobName=linux&configuration=linux_python3.7.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_python3.8.____cpython</td>
              <td>
                <a href="https://dev.azure.com/qgist/feedstock-builds/_build/latest?definitionId=1&branchName=master">
                  <img src="https://dev.azure.com/qgist/feedstock-builds/_apis/build/status/qgis-feedstock?branchName=master&jobName=linux&configuration=linux_python3.8.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_python3.6.____cpython</td>
              <td>
                <a href="https://dev.azure.com/qgist/feedstock-builds/_build/latest?definitionId=1&branchName=master">
                  <img src="https://dev.azure.com/qgist/feedstock-builds/_apis/build/status/qgis-feedstock?branchName=master&jobName=osx&configuration=osx_python3.6.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_python3.7.____cpython</td>
              <td>
                <a href="https://dev.azure.com/qgist/feedstock-builds/_build/latest?definitionId=1&branchName=master">
                  <img src="https://dev.azure.com/qgist/feedstock-builds/_apis/build/status/qgis-feedstock?branchName=master&jobName=osx&configuration=osx_python3.7.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_python3.8.____cpython</td>
              <td>
                <a href="https://dev.azure.com/qgist/feedstock-builds/_build/latest?definitionId=1&branchName=master">
                  <img src="https://dev.azure.com/qgist/feedstock-builds/_apis/build/status/qgis-feedstock?branchName=master&jobName=osx&configuration=osx_python3.8.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>win_python3.6.____cpython</td>
              <td>
                <a href="https://dev.azure.com/qgist/feedstock-builds/_build/latest?definitionId=1&branchName=master">
                  <img src="https://dev.azure.com/qgist/feedstock-builds/_apis/build/status/qgis-feedstock?branchName=master&jobName=win&configuration=win_python3.6.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>win_python3.7.____cpython</td>
              <td>
                <a href="https://dev.azure.com/qgist/feedstock-builds/_build/latest?definitionId=1&branchName=master">
                  <img src="https://dev.azure.com/qgist/feedstock-builds/_apis/build/status/qgis-feedstock?branchName=master&jobName=win&configuration=win_python3.7.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>win_python3.8.____cpython</td>
              <td>
                <a href="https://dev.azure.com/qgist/feedstock-builds/_build/latest?definitionId=1&branchName=master">
                  <img src="https://dev.azure.com/qgist/feedstock-builds/_apis/build/status/qgis-feedstock?branchName=master&jobName=win&configuration=win_python3.8.____cpython" alt="variant">
                </a>
              </td>
            </tr>
          </tbody>
        </table>
      </details>
    </td>
  </tr>
  <tr>
    <td>Linux_ppc64le</td>
    <td>
      <img src="https://img.shields.io/badge/ppc64le-disabled-lightgrey.svg" alt="ppc64le disabled">
    </td>
  </tr>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-qgis-green.svg)](https://anaconda.org/qgist/qgis) | [![Conda Downloads](https://img.shields.io/conda/dn/qgist/qgis.svg)](https://anaconda.org/qgist/qgis) | [![Conda Version](https://img.shields.io/conda/vn/qgist/qgis.svg)](https://anaconda.org/qgist/qgis) | [![Conda Platforms](https://img.shields.io/conda/pn/qgist/qgis.svg)](https://anaconda.org/qgist/qgis) |

Installing qgis
===============

Installing `qgis` from the `qgist` channel can be achieved by adding `qgist` to your channels with:

```
conda config --add channels qgist
```

Once the `qgist` channel has been enabled, `qgis` can be installed with:

```
conda install qgis
```

It is possible to list all of the versions of `qgis` available on your platform with:

```
conda search qgis --channel qgist
```




Updating qgis-feedstock
=======================

If you would like to improve the qgis recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`qgist` channel, whereupon the built conda packages will be available for
everybody to install and use from the `qgist` channel.
Note that all branches in the qgist/qgis-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](https://conda.io/docs/user-guide/tasks/build-packages/define-metadata.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](https://conda.io/docs/user-guide/tasks/build-packages/define-metadata.html#build-number-and-string)
   back to 0.

Feedstock Maintainers
=====================

* [@SrNetoChan](https://github.com/SrNetoChan/)
* [@ceholden](https://github.com/ceholden/)
* [@gillins](https://github.com/gillins/)
* [@kmuehlbauer](https://github.com/kmuehlbauer/)
* [@ocefpaf](https://github.com/ocefpaf/)

