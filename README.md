# OxfordAD2021
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/jjbernard/OxfordAD2021/HEAD)

Course repository for the 2021 version of my course at the University of Oxford

**WARNING**: The code will **NOT** work with Python 3.9 and above as `tensorflow` (which is the underlying tensor library for `Keras`) does not support Python 3.9. 
Python 3.8.X is advised (though it should probably work with Python 3.7.X and 3.6.X (but not below 3.6 as I use f-strings in the code)). 

## Seting-up the environment

Run the following commands:
```
$ python3 -m venv venv
$ source ./venv/bin/activate
(venv)$ pip install --upgrade pip
(venv)$ pip install -r requirements.txt
```

## Running the notebooks

From the same directory, simply do:
```
$ source ./venv/bin/activate
(venv)$ jupyter-notebook
```

You should be redirected to your browser from which you will be able to see and run the different notebooks
