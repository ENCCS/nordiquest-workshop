# Installation and setup

This page provides instructions for setting up the software environment
required to do the exercises in the lesson.
The following packages are needed:

- Python 3.7 or higher
- [Qiskit](https://qiskit.org/)
- [Quito](https://github.com/Simula-COMPLEX/quito)

## Local installation

It is strongly recommended to install all dependencies inside a virtual
environment. Here are instructions for using the `conda` package manager.

### Anaconda/miniconda

If you do not already have an Anaconda or miniconda installation on your
computer, download and install miniconda (a smaller distribution than Anaconda)
by following the [official documentation](https://docs.conda.io/en/latest/miniconda.html).

With a working Anaconda/miniconda installation, you can now create a new conda
environment with a recent Python version:

```console
$ conda create -n qcomp python=3
```

Before installing packages, activate the new environment:

```console
$ conda activate qcomp
```


### Qiskit

To install Qiskit, open a terminal window and type:

```console
   $ pip install qiskit
```

You will also need the visualization toolkit in Qiskit. To install it, type 

```console
$ pip install qiskit[visualization]
```

**Note:** If you are using the zsh terminal (standard on newer versions of MacOS), you need to use quotes:

```console
$ pip install 'qiskit[visualization]'
```

### Quito

First clone the Quito repository:

```console
$ git clone https://github.com/Simula-COMPLEX/quito.git
```

Then install its dependencies:

```console
$ pip install rpy2
```


## Running in the cloud

As an alternative to installing packages locally, you can also click the 
"launch binder" button on the front page. This will spin up a cloud instance 
on mybinder.org with all dependencies installed.



