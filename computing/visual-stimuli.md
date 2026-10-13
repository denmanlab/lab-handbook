<!-- Migrated from OSF 8erkh, wiki page "Visual Stimuli - psychopy". Original: https://osf.io/8erkh/wiki/Visual%20Stimuli%20-%20psychopy/ · last edited 2020-01-09. -->

# Visual Stimuli - psychopy

## Installation ##
Psychopy based stimuli and stimulus scripts should be run from an Anaconda environment called ```psychopy```. A new ```psychopy``` Anaconda envirnonment can be installed as such (on a Windows machine):

 1. Install an [Anaconda distribution](https://www.anaconda.com/distribution/), if not already installed 
 2. Make a new environment called ```psychopy```. Open the Anaconda command prompt (from the Start Menu, or search for it in Windows) and enter:
    > ```conda create --name psychopy python=3.7```
3. Activate the the ```psychopy``` environment by entering:
    >```activate psychopy```
4. Install psychopy:
    > ```pip install psychopy```
5. Install dependencies:
    > ```pip install PyDAQmx```

You are mostly done!
Also need:

 - toolbox  to get this, for now copy from somewhere (like //DENMANLAB/s1/software/pythonpackages/) to site-packages for the psychopy env. FUTURE: make a distro?
