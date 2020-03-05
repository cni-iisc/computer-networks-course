# Jupyter notebooks for Module 1 of the Networking course
This repository contains the notebooks that are designed as part of the online networking course offered by the Centre for Networked Intelligence.
 
## Setting up the local environment
To run these notebooks on your local machine, make sure that you have python installed, preferably version 3.x.

#### Installing Virtualenv for python
The next step is to install [`python-virtualenv`](https://docs.python-guide.org/dev/virtualenvs/), this creates an isolated environment to run different packages.  To install virtualenv, use the following command, for Linux and Unix

```bash
pip3 install virtualenv
```

In Windows, you can install virtualenv using just `pip` instead of `pip3`.

#### Starting the virtualenv and installing packages
The last step, before getting started on the notebooks will be to start the virtualenv and install the packages which is done by running the following commands:
  1. `source network-algo-dev-env/bin/activate` will be the start the python virtual environment 
  2. `pip install -r requirements.txt` will install all the packages that are not present (these packages are available only within the virtual environment)
  3. `jupyter notebook` will start the jupyter notebook server, and the notebooks can be accessed from the `notebooks/` directory
  4. Once you are done, you can exit from the python virtual environment by typing `deactivate`
  
