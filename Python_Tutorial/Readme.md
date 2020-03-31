# Python Tutorial
We recommend you to work with Jupyter Notebooks as most of the assignments will be provided in Jupyter Notebooks. Also it recommended to work online using Google Colab, so that you already have access to most of the python packages (i.e. no need to install them). If you want to work offline you can but support provided will be less (you need to google yourself) as if we go on solving package issues for everyone it will become very very difficult to complete the workshop on time.

## Starting the python tutorial
* Open this link [Python_Tutorial](Python_Tutorial.ipynb)
* Click the **Run in Google Colab** to run it online.
* Or download it by clicking the **Download notebook** link and save it to your notebook directory.

## Using Google Colab to run jupyter Notebooks (Recommended)
* [Get started with Google Colaboratory](https://www.youtube.com/watch?v=inN8seMm7UI)
* [Overview of Colaboratory Features](https://colab.research.google.com/notebooks/basic_features_overview.ipynb)

## Setup your environment to work locally on Python (Not Recommended)
I recommend using the [Anaconda distribution](https://www.anaconda.com/distribution/) to use python on your machine. Kindly follow the below steps to setup your machine:

**Install Anaconda:** Kindly follow the steps given at the link: [for windows here](https://docs.anaconda.com/anaconda/install/windows/) and [for linux here](https://docs.anaconda.com/anaconda/install/linux/). Make sure to install the Anaconda for python version 3.7

**Create a Virtual Environment:** I strongly suggests you to always work with using different environment setups for your different projects to manage their individual dependencies. So, create a separate environment for this workshop and other works related to **BCS Workshop'**.

### Creating Anaconda Virtual environment
* Open terminal in linux or Anaconda CMD in windows and run ```conda create --name bcs_iitk python=3.7 anaconda``` to create a virtual environment with name **bcs_iitk**
* To work inside this environment activate it before executing any python program, run ```conda activate bcs_iitk```
* Once, you are done with your work exit the environment by running ```conda deactivate```

### Running Jupyter Notebooks (local)
* Make a new directory ```mkdir bcs_iitk_workshop```
* Change your directory ```cd bcs_iitk_workshop```
* Run ```jupyter notebook``` in terminal (linux) or Anaconda CMD (windows)
* This will open a link in your browser where you will work with the jupyter notebooks.
