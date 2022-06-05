# Installation and setup

This page provides instructions for setting up the software environment
required to do the exercises in the lesson.
The following packages are needed:

- python=3.9
- numpy
- matplotlib
- jupyterlab
- qiskit
- qiskit[visualization]
- pylatexenc
- r-base=3.6
- r-tidyverse
- rpy2
- [Quito](https://github.com/Simula-COMPLEX/quito)

## Local installation

It is strongly recommended to install all dependencies inside a virtual
environment. Here are instructions for using the `conda` package manager.

### Anaconda/miniconda

If you do not already have an Anaconda or miniconda installation on your
computer, download and install miniconda (a smaller distribution than Anaconda)
by following the [official documentation](https://docs.conda.io/en/latest/miniconda.html).

With a working Anaconda/miniconda installation, you can now create a new conda
environment with all the required packages by:

```console
$ conda env create -f https://github.com/ENCCS/NordIQuEst-workshop/blob/main/environment.yml
```

Before using the environment you need to activate it:

```console
$ conda activate qcomp
```

### Quito

First clone the repository:

```console
$ git clone https://github.com/Simula-COMPLEX/quito.git
```

To use Quito one calls directly the script
`quito/Quito_CoverageRunning/quito.py`.

## Running in the cloud

As an alternative to installing packages locally, you can also click the 
"launch binder" button on the front page. This will spin up a cloud instance 
on mybinder.org with all dependencies installed.



