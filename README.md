# Exploratory Spatial Data Analysis with PySAL

**[Sergio Rey]**

**September 8, 2014**

**FOSS4G  2014, Portland, OR**

## Workshop Description

[PySAL] is a cross-platform library of spatial analysis functions written in Python. It is intended to support the development of high level applications for spatial analysis with an emphasis on vector spatial data. This tutorial will provide hands-on training in a select set of PySAL modules with a particular focus on spatial data processing, spatial autocorrelation analysis and visualization.

## Prerequisites

- Previous experience with Python programming is recommended
- Participants should bring their own laptops to the workshop
- Software should be installed prior to traveling to the workshop (instructions below)

### Software Requirements

For the workshop we will require the following packages be installed

- PySAL 1.8.0
- SciPy
- Numpy
- iPython Notebook 2.1+
- folium

There are a number of ways to install PySAL and these dependencies. For the workshop, if you do not yet have the dependencies installed we suggest using one of two scientific Python distributions (below). These have the advantages of including most of the dependencies for PySAL as well as PySAL itself. Moreover, both allow for updating PySAL to the most recent release  (1.8 released July 25, 2014) which is more current that what is listed in either distribution. Both of these distributions also allow for installation of our final dependency, folium.

#### PySAL via Anaconda Python Distribution

1. Install [Anaconda Python Distribution Version 1.8.0][Anaconda]
2. Open a terminal (Mac or Linux) or Powershell (Windows)
2. `pip install -U pysal`
3. `pip install -U folium`

#### PySAL via Enthought Canopy
Note that the Academic version of Canopy comes with PySAL version 1.7. For this workshop we will be using PySAL 1.8. Upgrading in Canopy can be done as follows:

1. Install [Canopy][Canopy]
2. Run Canopy
3. From the menu select `Tools Canopy Terminal`
4. `pip install -U pysal`
5. `pip install -U folium`



## Outline

- Part  1: Introduction and Setup (30 minutes)
	- PySAL Overview
	- Software Configuration Checks
	- IPython Notebook
- Part  2: PySAL for Spatial Data Processing (60 minutes)
	- Spatial Data Processing with PySAL
	- Spatial Weights
	- Visualization
- Break (15 Minutes)
- Part  3: PySAL for Exploratory Spatial Data Analysis (75 Minutes)
	- Global Spatial Autocorrelation Analysis
	- Local Spatial Autocorrelation Analysis

[PySAL]: http://pysal.org
[GeoDaSpace]: https://geodacenter.asu.edu/geodaspace-mode
[Anaconda]: http://continuum.io/downloads.html
[Canopy]: https://www.enthought.com/store
[VirtualBox]: https://www.virtualbox.org/wiki/Downloads
[VirtualBox 4.3.12]: http://download.virtualbox.org/virtualbox/4.3.12/VirtualBox-4.3.12-93733-Win.exe
[Vagrant]: http://www.vagrantup.com/downloads.html
[Vagrantfile]: Vagrantfile
[Sergio Rey]: https://geoplan.asu.edu/people/sergio-j-rey
