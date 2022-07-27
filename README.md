# Python-Scripts

# Pip installation on Linux  

### To Install pip securely in Linux servers
```sh
wget https://bootstrap.pypa.io/pip/2.7/get-pip.py
```
### Then run the following
```sh
python get-pip.py
```
<br>

# Virtualenv installation and setup in Python on Linux
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
> This creates a directory in the current path with the name of the environment (automation-env/). This directory contains the directories for installing modules and Python executables.
> 
### To specify the Python version to work with
Just use the argument `--python=/path/to/python/version virtualenv_name`
```sh
virtualenv --python=/usr/bin/python2.7 automation-env
```
or
```sh
virtualenv --python=/usr/bin/python3 automation-env
```
### Activate the Environment
Before you can start using the environment you need to activate it
```sh
source automation-env/bin/activate
```
> This ensures that only packages under automation-env/ are used. You will notice that the name of the environment is shown on the left of the prompt. This way you can see which is the active environment.

### Deactivate an Environment
After done working with the virtual environment deactivate it with
```sh
deactivate
```
> This puts back to the system’s default Python interpreter with all its installed libraries.

### To delete an Environment
Simply delete the environment folder.

<br>

# Fabric-python library installation on Linux
### To Install latest version of fabric 
```sh
pip install fabric
```
### Or to Install Older version of fabric 
```sh
pip install 'fabric<2.0'
```
