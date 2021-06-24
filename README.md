# MAUP
Supporting codes for analysis conducted as part of **The modifiable areal unit problem in geospatial least-cost electrification modelling** by [Babak Khavari](https://github.com/babakkhavari), [Andreas Sahlberg](https://github.com/AndreasSahlberg), [Will Usher](https://github.com/willu47), [Alexandros Korkovelos](https://github.com/akorkovelos) and [Francesco Fuso Nerini](https://github.com/FFusoNerini)

## Content
This repository contains:
* An environment .yml file needed for generating a fully functioning python 3.7 environment necessary for the clustering algorithm.
* The clustering code and related functions. These files also contain necessary steps in order to reproduce results.
* An example case for Benin.

## Installing and running the clustering notebook

**Requirements**

The clustering module (as well as all supporting scripts in this repo) have been developed in Python 3. We recommend installing [Anaconda's free distribution](https://www.anaconda.com/distribution/) as suited for your operating system. 

**Install the clustering repository from GitHub**

After installing Anaconda you can download the repository directly or clone it to your designated local directory using:

```
> conda install git
> git clone https://github.com/babakkhavari/Clustering.git
```
Once installed, open anaconda prompt and move to your local "clustering" directory using:
```
> cd ..\Clustering
```

In order to be able to run the clustering tool (main.ipynb and funcs.ipynb) you have to install all necessary packages. "full_project.yml" contains all of these and can be easily set up by creating a new virtual environment using:

```
conda env create --name clustering --file full_project.yml
```

This might take some time. When complete, activate the virtual environment using:

```
conda activate clustering
```

With the environment activated, you can now move to the clustering directory and start a "jupyter notebook" session by simply typing:

```
..\Clustering> jupyter notebook 
```
## Changelog
**5-April-2020**: Original code base published

## Resources
Original dataset can be found here: https://data.mendeley.com/datasets/z9zfhzk8cr

Journal article can be found here: https://www.nature.com/articles/s41597-021-00897-9
## Credits

**Conceptualization:** [Babak Khavari](https://github.com/babakkhavari) & [Francesco Fuso-Nerini](https://github.com/FFusoNerini)<br />
**Methodology:** [Babak Khavari](https://github.com/babakkhavari)<br />
**Software:** [Babak Khavari](https://github.com/babakkhavari)<br />
**Validation:** [Babak Khavari](https://github.com/babakkhavari), [Alexandros Konrkovelos](https://github.com/akorkovelos) & [Andreas Sahlberg](https://github.com/AndreasSahlberg)<br />
**Supervision and Advisory support:** [Francesco Fuso-Nerini](https://github.com/FFusoNerini) & [Mark Howells](https://orcid.org/0000-0001-6419-4957)<br />
