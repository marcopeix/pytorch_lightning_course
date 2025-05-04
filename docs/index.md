## pytorch_lightning_course

This self-paced, recorded bootcamp is designed to take learners from the basics of deep learning with PyTorch to advanced model deployment with PyTorch Lightning. The curriculum is structured into clear modules, each combining theory with hands-on coding exercises. It caters to both beginners (new to PyTorch) and advanced users by covering foundational concepts, famous model architectures, practical implementations in Lightning

## Setting up environment 

For setting up the environment we will be using conda/mamba. I recommend using the mamba which is very fast and efficient in managing the dependency resolvance. Please follow along the listed below steps to setup the environment 

Step 1: Install Micromamba or miniconda package managers.
> [Installation guidelines for micromamba](https://mamba.readthedocs.io/en/latest/installation/micromamba-installation.html)

> [Installation guidelines for miniconda](https://www.anaconda.com/docs/getting-started/miniconda/install)


Step 2: Install the environment with respective commands 
```bash
# replace with right file path for env.yml, current command assumes your in the root directory 
mamba env create --file {env.yml} 

```

> If your using conda please use this to install the environment 

```bash
# replace with right file path for env.yml, current command assumes your in the root directory 
conda env create --file {env.yml}
```

Step 3: Activate the Environment 

```bash

conda activate lightning_course

```