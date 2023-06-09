# Building Deep Learning using Pytorch

This is a repository deeply inspird by Atcold
[https://github.com/Atcold/pytorch-Deep-Learning]

# Getting started

To be able to follow the exercises, you are going to need a laptop with Miniconda (a minimal version of Anaconda) and several Python packages installed.
The following instruction would work as is for Mac or Ubuntu Linux users, Windows users would need to install and work in the [Git BASH](https://gitforwindows.org/) terminal.

## Download and install Miniconda

Please go to the [Anaconda website](https://conda.io/miniconda.html).
Download and install _the latest_ Miniconda version for _Python_ 3.7 for your operating system.

```bash
wget <http:// link to miniconda>
sh <miniconda*.sh>
```

## Check-out the git repository with the exercise

Once Miniconda is ready, checkout the course repository and proceed with setting up the environment:

```bash
git clone https://github.com/Atcold/pytorch-Deep-Learning
```

## Create isolated Miniconda environment

Change directory (`cd`) into the course folder, then type:

```bash
# cd pytorch-Deep-Learning
conda env create -f environment.yml
source activate pDL
```

## Start Jupyter Notebook or JupyterLab

Start from terminal as usual:

```bash
jupyter lab
```

Or, for the classic interface:

```bash
jupyter notebook
```

## Notebooks visualisation

_Jupyter Notebooks_ are used throughout these lectures for interactive data exploration and visualisation.

We use dark styles for both _GitHub_ and _Jupyter Notebook_.
You should try to do the same, or they will look ugly.
JupyterLab has a built-in selectable dark theme, so you only need to install something if you want to use the classic notebook interface.
To see the content appropriately in the classic interface install the following:

- [_Jupyter Notebook_ dark theme](https://userstyles.org/styles/153443/jupyter-notebook-dark);
- [_GitHub_ dark theme](https://userstyles.org/styles/37035/github-dark) and comment out the `invert #fff to #181818` code block.
