# PyData Workshop: Keep the Data Flowing
Welcome to our GitHub repository for the PyData workshop!

## Intro
We use the python package [great_expecations](#https://greatexpectations.io) to create expectations for our ingress data. This workshop teaches you the basics on how to implement and use this package.

## Installation

### Simple
```
$ python -m pip install -r ./requirements.txt
```

### Virtualenv
```
$ python3 -m venv great-expectations-workshop
```

*Windows:*  
```
$ great-expectations-workshop\Scripts\activate.bat
$ python -m pip install -r requirements.txt
$ python -m ipykernel install --name great-expectations-workshop
```
*MacOS/Unix:*  
```
$ source great-expectations-workshop/bin/activate
$ python -m pip install -r requirements.txt
$ python -m ipykernel install --name great-expectations-workshop
```
### Conda
```
$ conda create -n great-expectations-workshop pip -y
$ conda activate great-expectations-workshop
$ python -m pip install -r requirements.txt
$ python -m ipykernel install --name great-expectations-workshop
```


## Setting up for part 1
`$ cd <repository directory>`
`$ jupyter notebook`
open `workshop-pydata-part1.ipynb`


## Create basic project

### Initialization

`$ create_expectations init`

