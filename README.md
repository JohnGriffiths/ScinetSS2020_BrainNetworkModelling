# Scinet Summer School 2020: Introduction to Brain Network Modeling

[![Open in Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/JohnGriffiths/ScinetSS2020_BrainNetworkModelling/master) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/JohnGriffiths/ScinetSS2020_BrainNetworkModelling/)


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


### If you're using Binder

Click on the `Open In Binder` badge above, and wait patiently for the image and environment to be built and initiated. 


### If you're using Google Colab

Click on the `Open In Colab` badge above, and wait patiently for the environment to be initiated. 

Note - in google colab you need to `pip install` non-standard libraries. Each of the notebooks has a commented out section that needs to be un-commented and run in order to make the libraries available on Colab. 


### For course attendees:


#### Login information

See [here](https://support.scinet.utoronto.ca/education/go.php/540/index.php/ib/1/) for the scinet course webpage

To access the jupyterhub: 

- Click 'log in' in the top right. Enter your login details
- From the [course website](https://support.scinet.utoronto.ca/education/go.php/540/index.php), click 'login information for cluster'
- Follow the instructions: go to the scinet jupyterhub site, and enter the uname/pwd displayed on the previous page
- Follow the jupyterhub instructions above

#### Homework assignment

The homework assignment for the course can be found in `notebooks/homework_assignment.ipynb`

This follows on from the `intro_to_whole_brain_modelling.ipynb` notebook, which is the basis of the practical session. 

Completed assignments should be uploaded to the designated folder on the [course website](https://support.scinet.utoronto.ca/education/go.php/540/index.php).

These should take the form of jupyter notebooks that are extended from `homework_assignment.ipynb`. 

