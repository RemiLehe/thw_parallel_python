[![Binder](http://mybinder.org/badge.svg)](http://mybinder.org:/repo/remilehe/thw_parallel_python)

# Overview

Repository for a tutorial at [THW, Berkeley](http://www.thehackerwithin.org/berkeley/) on parallel programming in Python.

This short tutorial introduces parallel programming with `mpi4py` and
`concurrent.futures`, and applies it to recognition of hand-written
digits.

# Running the tutorial

The tutorial is in the form of Jupyter notebooks. You can run these
notebooks:

- **remotely** on [mybinder.org](http://mybinder.org/): to do so,
click the above badge.
- **locally** on your computer. To do so, install
[Anaconda](https://www.continuum.io/downloads) and install the
requirements by typing
```
conda env create -n parallel_python -f install/environment.yml
source activate parallel_python
```
