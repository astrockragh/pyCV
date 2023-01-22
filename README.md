# cosvar (pyCV)

Python package based on the IDL code released with the Cosmic Variance Cookbook of Moster et al. (2010)

The code is based on galaxy stellar mass bins (as described in https://arxiv.org/pdf/1001.1737.pdf), scaled to dark matter cosmic variance (as described in https://arxiv.org/pdf/astro-ph/0109130.pdf). 

This is significantly more useful than dark matter - only variance, since the empirical galaxy variance is significantly higher.

Main package is in src/pyCV.py. The only dependencies are numpy, scipy and pandas.


```
cosvar
│   README.md
│   LICENSE    
│   setup.py
└───src
    │   __init__.py
    │   pyCV.py 
           - quickcv.py 
             - intpk4.py/dlin.py/rz.py
               -pofk.py
    
```
