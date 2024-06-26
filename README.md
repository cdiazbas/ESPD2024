# ESPD2024
A Machine Learning tutorial on how to build your Flare and CME predictor at the 1st European Solar Physics Division (ESPD) summer school: Energisation and heating in the solar plasma 29 April - 3 May 2024 Dubrovnik, Croatia. Google slides with the content available in [here](https://docs.google.com/presentation/d/1JaH5CGhRQkHw73t148zPNwxYjgyYuETgv-dpznYFIaA/edit?usp=sharing).


### Run locally:
To run this notebook locally, we suggest that you create a new conda environement using the `environment.yml` file in this repository. This can be done by first cloning this repository i.e. `git clone https://github.com/cdiazbas/ESPD2024` and then creating a new environment as such from the `ESPD2024` folder:

```
$ conda env create -f environment.yml
$ conda activate espd_machinelearning
$ jupyter lab
```
The jupyter lab will open our repository with all the notebooks in your browser. 

If you already have a conda environment, simply install the packages using `pip install -r requirements.txt`.

If you need to remove the environment, simply run the following command: `conda env remove -n espd_machinelearning`.


### Run using Google Colab:
You can run the notebooks in this repository using Google Colab by clicking on the following links:
- [Flare Prediction](https://colab.research.google.com/github/cdiazbas/ESPD2024/blob/main/flare_notebook.ipynb)
- [CME Prediction](https://colab.research.google.com/github/cdiazbas/ESPD2024/blob/main/cme_notebook.ipynb)
- [CME arrival time](https://colab.research.google.com/github/cdiazbas/ESPD2024/blob/main/transitTime_notebook.ipynb)

Remember that changes in the notebooks will not be saved, unless you copy the notebooks to your Google Drive.


### Run using BinderHub:
If you want you can run this notebook using Binder by clicking on this link:
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/cdiazbas/ESPD2024/HEAD). 
It may take a few minutes to load up when you click on it for the first time
