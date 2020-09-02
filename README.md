# read_miles
Code to read MILES SSP models downloaded from:
http://research.iac.es/proyecto/miles/pages/webtools/tune-ssp-models.php
Provides option to filter models by age and metallictities.

**Note:** assumes the default wavelength setup on the webpage, i.e. linear wavelength spacing with lmd_start = 3540.5 and Delta_lmd = 0.9.

# installation
Clone this repository into a directory which is in your PYTHONPATH e.g. 
```
my_python_library/read_miles
```
where
```
echo $PYTHONPATH
my_python_library
```

# requirements
astropy

# usage
Details in docblock of MilesSSPs class. Example shown in ipython notebook.





