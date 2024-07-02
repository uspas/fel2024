# USPAS FEL 2024 Class
Repository for solutions and work in progress changes to the lab portion of VUV and X-ray Free Electron Lasers course (summer 2024).


# Installation 

The software for the class will run natively on Linux and macOS. Windows users will need to install a Linux distribution (e.g. Ubuntu) using WSL2.


## Install Miniforge

Download and install Minforge using the instructions at: https://github.com/conda-forge/miniforge?tab=readme-ov-file#download. Note that:
- If you have a Mac with an M1, M2, or M3 processor, use the "Apple Silicon" link. For older MacBooks, use the x86-64 version. If unsure, click the Apple at the top left of your screen, "About this Mac" and look at the "Chip" line.
- For Windows on WSL2, choose the Linux x86-64 version (**not** the Windows build!).

Once installd, initialize conda on the command line with:



```bash
conda init
```

## Clone this repository
The class will use this respository for all data. Please clone this repository using [GitHub Desktop](https://github.com/apps/desktop) or using `git` on the command line. 

Note that this repository will be updated periodically during the class.

## Create the `fel2024` environment

This repository contains a file `environmentl.yml`. Install on the command line:
```bash
conda env create -f environment.yml
```

Now activate the `fel2024` environment:
```bash
conda activate fel204
```
and test that Jupyter lab works:
```
jupyter lab
```


## Download Genesis4 examples 
Download LUME-Genesis' Genesis4 examples: [lume_genesis_genesis4_examples](https://github.com/slaclab/lume-genesis/releases/download/v1.0.0/lume_genesis_genesis4_examples_v1.0.0.zip).

Try these using Jupyter lab in the `fel2024` environment.

