# Scinet Summer School 2020: Introduction to Brain Network Modeling

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/JohnGriffiths/ScinetSS2020_BrainNetworkModelling/master)


### Developed by
- John Griffiths

( With essential contributions from: Julie Courtiol, Amanda Easson, Kelly Shen, Jerry Jeyachandra )



### If you're using SciNet's JupyterHub System


1. Log into on the [scinet jupyterhub website](njupyter.scinet.utoronto.ca)

2. First time only: add the course's conda env to your conda envs list:

Open up a terminal from the jupyterhub landing page

```bash
module load intelpython3
conda config --append envs_dirs /scinet/course/ss2020/8_brainnetwork/env
```

Return the the landing page and refresh the browser. You should see the `ss2020_tvb` option now when clicking the `new` menu on the top right

3. Also first time only: clone the github repo for the course in a terminal

```bash
git clone https://github.com/JohnGriffiths/ScinetSS2020_BrainNetworkModelling
```

4. Navigate to the `notebooks` folder in the downloaded github repo folder, and open up the course notebooks 


### If you're using Google Colab

To run on Google Colab:

Go to https://colab.research.google.com.

Click File --> Open --> Github

Copy and paste this URL: https://github.com/johngriffiths/ScinetSS2020_BrainNetworkModelling, then press Enter.

Choose the `intro_to_whole_brain_modelling.ipynb` or `modelling_resting_state.ipynb` notebook

Note - in google colab you need to `pip install` non-standard libraries. Each of the notebooks has a commented out section that needs to be un-commented and run in order to make the libraries available on Colab. 


### If you're using Binder

Click on the binder badge above and wait patiently for the environment to be built and initiated. 

