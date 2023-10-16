# pm21-rabbit

## Introduction

This is the course material for PM-21, Winter Semester 2023-2024 (year of the
Rabbit), Faculty of Biology, University of Freiburg. The instructors are Prof.
Dr. Andrew Straw and Dr. Michael Harrap.

## Run interactively at https://strawlab-rp2.zoologie.uni-freiburg.de

You have the choice of running the exercises in the class either (A) on our
Jupyter server at https://strawlab-rp2.zoologie.uni-freiburg.de (login details
will be discussed in class) or (B) on your own PC.

To run on your PC, we recommend using
[Mamba](https://mamba.readthedocs.io/en/latest/installation.html) to install
Python and the dependencies we will use. We will help you install Mamba and the
packages we use in the course. Until Anaconda/Mamba is installed on your own PC,
for the first few days (or for the entire course), you may use our Jupyter
server. This will be taken offline shortly after the course is done.

## Installation with Anaconda

Download the Anaconda Distribution from
[here](https://www.anaconda.com/download). (As a faster command-line alternative
to Anaconda, you may be interested in
[mamba](https://mamba.readthedocs.io/en/latest/installation.html)).

We will demonstrate how to setup an Anaconda environment in class. Use our
[`environment.yml`](https://raw.githubusercontent.com/strawlab/pm21-rabbit/main/environment.yml)
file to setup your `pm21-rabbit` environment in Anaconda.

**Not using the
`environment.yml` file for the class will likely result in incompatibility with
the exercises in the course. This is because different versions of the packages
used will probably be installed.**


Using the command line:

```
conda env create -f environment.yml
conda activate pm21-rabbit
```

Now you can start jupyter on your PC:

```
jupyter notebook
```

## The Python Tutor - extremely highly recommended

http://pythontutor.com/

## Troubleshooting

### Note for macOS users

Before starting `jupyter notebook` from the command line, you may like to type:

    ulimit -n 4096

This will solve [OSError: [Errno 24] Too many open files](https://github.com/jupyterlab/jupyterlab/issues/6727).

## Code of conduct

Anyone who interacts with this software in any space, including but not limited
to this GitHub repository, must follow our [code of
conduct](code_of_conduct.md).
