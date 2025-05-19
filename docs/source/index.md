# Welcome to ONTraC (Ordered Niche Trajectory Construction)

<span>
  <a href="https://pypi.org/project/ONTraC/">
    <img src="https://img.shields.io/pypi/v/ONTraC.svg" alt="PyPI version" style="display:inline-block;">
  </a>
  <a href="https://pypi.org/project/ONTraC/">
    <img src="https://img.shields.io/pypi/pyversions/ONTraC.svg" alt="Python versions" style="display:inline-block;">
  </a>
  <a href="https://pepy.tech/project/ONTraC">
    <img src="https://static.pepy.tech/badge/ONTraC" alt="Downloads" style="display:inline-block;">
  </a>
  <a href="https://pypi.org/project/ONTraC/">
    <img src="https://img.shields.io/pypi/dm/ONTraC.svg" alt="PyPI Downloads" style="display:inline-block;">
  </a>
  <a href="https://anaconda.org/gyuanlab/ontrac">
    <img src="https://anaconda.org/gyuanlab/ontrac/badges/version.svg" alt="Anaconda-Server Version" style="display:inline-block;">
  </a>
  <a href="https://anaconda.org/gyuanlab/ontrac">
    <img src="https://anaconda.org/gyuanlab/ontrac/badges/platforms.svg" alt="Anaconda-Server Platforms" style="display:inline-block;">
  </a>
  <a href="https://github.com/gyuanlab/ONTraC">
    <img src="https://badgen.net/github/stars/gyuanlab/ONTraC" alt="GitHub Stars" style="display:inline-block;">
  </a>
  <a href="https://github.com/gyuanlab/ONTraC/issues">
    <img src="https://img.shields.io/github/issues/gyuanlab/ONTraC.svg" alt="GitHub Issues" style="display:inline-block;">
  </a>
  <a href="https://github.com/gyuanlab/ONTraC/blob/master/LICENSE">
    <img src="https://img.shields.io/github/license/gyuanlab/ONTraC.svg" alt="GitHub License" style="display:inline-block;">
  </a>
</span>

ONTraC (Ordered Niche Trajectory Construction) is a niche-centered, machine
learning method for constructing spatially continuous trajectories.

ONTraC differs from existing tools in that it treats a niche, rather than an
individual cell, as the basic unit for spatial trajectory analysis. In this
context, we define niche as a multicellular, spatially localized region where
different cell types may coexist and interact with each other.

ONTraC seamlessly integrates cell-type composition and spatial information by
using the graph neural network modeling framework. Its output, which is called
the niche trajectory, can be viewed as a one dimensional representation of the
tissue microenvironment continuum. By disentangling cell-level and niche-level
properties, niche trajectory analysis provides a coherent framework to study
coordinated responses from all the cells in association with continuous tissue
microenvironment variations.

```{image} ../source/images/other/ONTraC_structure.png
```

Check out the [installation](./installation.rst) for installation guidelines.

Check out the [usage](./usage.rst) for details if you want to use ONTraC with command lines.

Check out the [step-by-step tutorial](./step_by_step_tutorial.ipynb) for details if you want to use ONTraC within a Jupyter notebook.

```{toctree}
:hidden: true

installation
usage
tutorials
examples
contributors
citation
```

```{note}
This project is under active development.
```
