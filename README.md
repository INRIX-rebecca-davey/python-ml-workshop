# Python ML workshop

## What's going to happen

At the workshop we'll be spending a couple of hours working through a machine learning problem from start to finish. We'll switch between quick 'taught' sections on slides, and interactive sections where you'll be using Jupyter notebook and various packages to write code for working with the data and developing the machine learning model.

Here's our schedule for the evening:

18.30 - 19.30: part 1

19.30 - 20.00: pizza, drinks, chit chat

20.00 - 21.00: part 2

Our offices will be open from 6pm so if you're having issues with setup then feel free to drop by from 6 and we'll help you out. Equally, feel free to stick around for a chat afterwards.

## Jupyter notebook

The tool we'll be using to develop and run the code is Jupyter notebook. This is a Python package that will be installed when you install the dependencies for the workshop. You launch it from the command line with 'jupyter notebook' and it will start up in whatever directory you launch it from. It runs in the browser from localhost. Notebooks have the file type '.ipynb' and if you have these files in the directory you launch Jupyter from, these will show up as notebooks you can interact with in the Jupyter interface.

If you haven't used Jupyter notebook before, do not fear as there are plenty of good tutorials out there. Here's a quick one that covers the basics: http://cs231n.github.io/ipython-tutorial/

We'll also be using a wonderful package called 'pandas', which uses dataframes for neat handling of our data. If you haven't used it before, check out the pandas tutorial notebook 'pandas_tutorial.ipynb' to get a feel for the basic functions, as we'll be using it quite a lot.

## The dataset

In the 'data' directory you'll find the data we'll be looking at tonight. It describes all road traffic accidents in Leeds from 2009 to 2015 that involve at least a minor injury. As you'll see, there are many interesting features to work with, including road surface conditions, lighting conditions, number of vehicles involved etc. 

We've provided the raw files of the separate years, and additionally the following files:

* all.csv - all raw year files together
* cleaned-with-latlng.csv - several data cleaning steps applied to all.csv, described in 'cleaning-steps.txt'

Link to data on data.gov.uk site: https://data.gov.uk/dataset/road-traffic-accidents

We chose this dataset for a few reasons:
* it's relevant to our own work! We love traffic data.
* it's (nearly) local, just a short hop across the Penines away
* it has so many features! Great for machine learning, and rich for visualisation and mapping.

## Installing the tools we'll be using

We'll be using several Python libraries in the workshop, and depending on how/if you have Python installed there are different ways to get these ready...

### If you don't currently have Python installed

There are different ways to install Python but the one I'd recommend if starting from scratch is via miniconda.

Compared to the Anaconda distribution, which installs Python and then a tonne of packages, miniconda just installs Python and conda. conda is the package manager used to fetch more packages as and when you need them, and it also manages environments.

Follow the instructions here for your OS: https://conda.io/miniconda.html

Once installed, to get the packages/environment we'll be using you should download the environment.yml file above and create an environment from it using the command 'conda env create -f environment.yml' in whatever directory you downloaded the file to.

You can then activate this environment using 'activate mlworkshop' (mlworkshop is the name we gave to the environment)

### If you already have Python installed via conda/Anaconda/Miniconda

Use the environment.yml file above to install the packages/environment we'll be using. You can do this by running the command 'conda env create -f environment.yml' in whatever directory you downloaded the yml file into.

You can then activate this environment using 'activate mlworkshop' (mlworkshop is the name we gave to the environment)

### If you already have Python installed NOT using conda/Anaconda/miniconda

You can either...
- use pip to get the packages listed in the environment.yml file, using 'pip install PACKAGENAME' commands
- install miniconda/Anaconda on top of your existing Python install. It will manage Python versions and installations for you.

## Contact

Remember, if you have any questions or run into any problems you can reach us at datascienceevents@inrix.com


