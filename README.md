# MoorPy - Quasi-Static Mooring Analysis in Python

MoorPy is a design-oriented mooring system library for Python based around a quasi-static modeling approach.

### Prerequisites

- Python 3.7 or greater
- The following packages: NumPy, MatPlotLib, yaml, scipy

### Installation
From the command line in thh main MoorPy directory, run the following commands based on your additional needs...

#### General
```pycon
pip install .
```

#### Development
```pycon
pip install .[dev]
```
#### Testing
```pycon
pip install .[test]
pre-commit install --hook-type pre-commit --hook-type pre-push
```
#### Documentation
```pycon
pip install .[docs]
```

MoorPy's documentation website is under development at https://moorpy.readthedocs.io

### Citing
The MoorPy software can be cited as:
M. Hall, S. Housner, S. Sirnivas, and S. Wilson.
*MoorPy: Quasi-Static Mooring Analysis in Python.*
National Renewable Energy Laboratory, 2021.
https://doi.org/10.11578/dc.20210726.1.
