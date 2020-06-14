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

## Create basic project

### Initialization

```
great_expectations init  
First, Great Expectations will create a new directory:  
    OK to proceed? [Y/n]: Y  
  
Would you like to configure a Datasource? [Y/n]: Y  
  
What data would you like Great Expectations to connect to?
  1. Files on a filesystem
  
What are you processing your files with?  
  1. Pandas
  
Enter the path (relative or absolute) of the root directory where the data files are stored.
  ./data
  
Give your new Datasource a short name.
  [data__dir]: weather_data

Great Expectations will now add a new Datasource 'weather_data' to your deployment, by adding this entry to your great_expectations.yml:
  Would you like to proceed? [Y/n]: Y

Would you like to profile new Expectations for a single data asset within your new Datasource? [Y/n]: n
```
