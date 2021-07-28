# MAUP
Supporting codes for analysis conducted as part of **The modifiable areal unit problem in geospatial least-cost electrification modelling** by [Babak Khavari](https://github.com/babakkhavari), [Andreas Sahlberg](https://github.com/AndreasSahlberg), [Will Usher](https://github.com/willu47), [Alexandros Korkovelos](https://github.com/akorkovelos) and [Francesco Fuso Nerini](https://github.com/FFusoNerini)

## Content
This repository contains:
* An environment .yml file needed for generating a fully functioning python 3.7 environment necessary for the codes in this repository.
* The DBSCAN code used for the DBSCAN clustering. 
* The code used in order to conduct the sensitivity analysis (based on [SALib](https://github.com/SALib/SALib)).
* And the OnSSET version used in order to generate the least-cost electrification results

## Installing and running the notebooks

**Requirements**
*NOTE:* The requirements below refer to running the two notebooks on this repository (DBSCAN clustering and SALib). In case you wish to run the OnSSET codes instructions follows in a later section.  

The MAUP module (as well as all supporting scripts in this repo) have been developed in Python 3. We recommend installing [Anaconda's free distribution](https://www.anaconda.com/distribution/) as suited for your operating system. 

**Install the repository from GitHub**

After installing Anaconda you can download the repository directly or clone it to your designated local directory using:

```
> conda install git
> git clone https://github.com/babakkhavari/MAUP.git
```
Once installed, open anaconda prompt and move to your local "MAUP" directory using:
```
> cd ..\MAUP
```

In order to be able to run the codes available, you have to install all necessary packages. "full_project.yml" contains all of these and can be easily set up by creating a new virtual environment using:

```
conda env create --name MAUP --file full_project.yml
```

This might take some time. When complete, activate the virtual environment using:

```
conda activate MAUP
```

With the environment activated, you can now move to the clustering directory and start a "jupyter notebook" session by simply typing:

```
..\MAUP> jupyter notebook 
```
## Changelog
**24-June-2021**: Original code made public
**28-July-2021**: Cleaned up the notebooks

## Resources
Dataset can be found here: #TODO: ADD MENDELEY REPO WHEN MADE PUBLIC 

Journal article can be found here: #TODO: ADD WHEN MADE PUBLIC
