# Python ML workshop

## When and where

The office will be accessible from 6pm for a 6.30pm start. We'll be taking a break halfway through for food and drink, and aiming to finish at 9pm.

The INRIX office is at Station House in Altrincham, just opposite the train/tram station. Closer to the event you'll receive information about access.

If you have any questions at all then please get in touch: datascienceevents@inrix.com

## What's going to happen

Description of what we'll be doing and what the goal is.

"So with all this in mind, we’re hosting an interactive machine learning workshop where we’ll use Python to build a machine learning model of a dataset, going through step-by-step and explaining the concepts we’re applying."

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

### If you don't currently have Python installed

There are a couple of options...

You can install Python directly from https://www.python.org/downloads/, and then install the required packages separately (see below).

Or you can install everything (including Python) via Anaconda, in one of two ways:
- install the 'full' Anaconda distribution (437MB), which includes everything we'll be using, but also lots of other packages we won't be using 
- install 'Miniconda' which is some essentials, including Python and conda, the tool used to install packages via Anaconda. This way you can install just the packages we'll be using, but all from one place. Miniconda: https://conda.io/miniconda.html

### If you already have Python installed via conda/Anaconda/Miniconda

You could...
* use the soon-to-be environment.yml file to create a conda environment with all the libraries we'll be using!
* use conda to install the packages separately, with 'conda install PACKAGENAME'

### If you already have Python installed directly (no conda/Anaconda/Miniconda)

You can either...
- use pip to get the packages, with 'pip install PACKAGENAME'
- install miniconda/Anaconda over the top of your current Python?

### What is Anaconda/conda and how does conda work?

Anaconda is a distribution that includes Python and a whole host of useful packages and libraries, including all that we'll be using. Anaconda also includes 'conda', which is a command line tool for managing and installing new packages.


