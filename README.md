# Analyzing Public Data on Rec Center Customers

A demographic analysis of users of the Recreation Center network in Boulder Colorado, along with the membership packages they use (or do not use) to access the network.

![](pool.jpg)  

## Installation/Dependencies:

Assumes use of `conda` - can be replaced with other method for managing virtual environments and packages.
```
git clone https://github.com/chapman-mcd/rec_center_demographics
conda create -n rec-center
conda activate rec-center
conda install numpy pandas matplotlib seaborn scikit-learn jupyter
pip install zipcodes geopy
```  

Also required is the demographic data which can be downloaded [here](https://open-data.bouldercolorado.gov/datasets/121a6643af894314bd02ea42544ce9d9_0).  

## Included files:
Project_RecreationCenters_Boulder.ipynb : Jupyter notebook containing primary analysis  
various supporting images, either used in the notebook or extracted from it for the resulting [blog post](https://chapman-mcdaniel.medium.com/lets-see-who-s-down-at-the-rec-center-f5f7a2f888b4).

## Results:
* Rec Center customers live nearby, are evenly distributed male/female, and are well represented across ages apart from a dip between 15 and 25.  
* Relatively few customers purchase punch cards or memberships, preferring to pay per-visit. Due to the broad reach of Rec Center customers overall, increasing this seems like a reasonable focus.  
* There are notable trends in which types of packages are most attractive to which customers, and machine learning could be used to guide what sort of offers to present each person.  

## Acknowledgements:
Boulder County Open Data Initiative, python itself and all dependency packages (without which this project would not be possible), Udacity, and my mother for taking me to the swim at the Rec Center so many times.

Part of Data Scientist Nanodegree at Udacity
