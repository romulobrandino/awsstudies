# Python in Microsoft WSL 2 

## Set up your development environment

## Install Python, pip, and venv

In WSL2 Ubuntu 18.04 LTS buntu 18.04 LTS comes with Python 3.6 already installed, but it does not come with some of the modules that you may expect to get with other Python installations. We will still need to install pip, the standard package manager for Python, and venv, the standard module used to create and manage lightweight virtual environments.

Confirm that Python3 is already installed by opening your Ubuntu terminal and entering: ```python3 --version```. This should return your Python version number. If you need to update your version of Python, first update your Ubuntu version by entering: sudo apt update && sudo apt upgrade, then update Python using ``sudo apt upgrade python3``.

Install pip by entering: sudo apt install python3-pip. Pip allows you to install and manage additional packages that are not part of the Python standard library.

Install venv by entering: ``sudo apt install python3-venv``.


## Create a virtual environment


* Create a virtual environment, for example name '.venv': ``python3 -m venv .venv``