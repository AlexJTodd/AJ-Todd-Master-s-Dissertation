This repository contains most of the code developed over the course of my Master's dissertation, as well as a comprehensive list of every reference I used. The code was written in Spyder and Jupyterlab. Numba is extensively used here -- it writes Python functions directly into C, which increases the speed at which functions can be executed. Especially for the time-dependent method used here, where the computational expense is great, Numba allows these methods to be executed without great effort.

NOTE: If the code does not run because a specific package is not installed, for instance "scienceplots", type in the console
pip install scienceplots

The same applies for packages such as numba, as well as the plotting software I have used.
