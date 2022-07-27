# Python-Scripts

# Pip Installation for Linux  

### To Install pip securely in Linux servers
```sh
wget https://bootstrap.pypa.io/pip/2.7/get-pip.py
```
### Then run the following
```sh
python get-pip.py
```

# Virtualenv in Python
### What is virtualenv?
***"virtualenv"*** is a tool used to create isolated Python environments. It creates a folder which contains all the necessary executables to use the packages that a Python project would need.
 ### To Install virtualenv with pip
 ```sh
pip install virtualenv
```
```sh
virtualenv --version
```
### To create a virtual environment now
```sh
virtualenv automation-env
```
This creates a directory in the current path with the name of the environment (automation-env/). This directory contains the directories for installing modules and Python executables.


# To Install Fabric-python library, in Linux
### To Install latest version of fabric 
```sh
pip install fabric
```
### Or to Install Older version of fabric 
```sh
pip install 'fabric<2.0'
```
