# ml-lab-1: Practice github classroom

1. Clone this repository to your local computer.
2. Open Jupyter notebook `ml-lab-1.ipynb`
3. Change author name to your name. 
4. Save. git add and commit change.
5. Copy the code below and run in a code cell in Jupyter notebook.
6. Save. git add and commit change.
7. Run the second cell to display all conda environments. 
8. Save. git add and commit change.
9. git push changes to github.


```Python
import sys
print("Python version:", sys.version)

import pandas as pd
print("pandas version:", pd.__version__)

import matplotlib
print("matplotlib version:", matplotlib.__version__)

import numpy as np
print("NumPy version:", np.__version__)

import scipy as sp
print("SciPy version:", sp.__version__)

import IPython
print("IPython version:", IPython.__version__)

import sklearn
print("scikit-learn version:", sklearn.__version__)

import yellowbrick
print("yellowbrick version:", yellowbrick.__version__)
```

For me, the package versions are:
```
Python version: 3.8.8 (default, Apr 13 2021, 12:59:45) 
[Clang 10.0.0 ]
pandas version: 1.2.4
matplotlib version: 3.3.4
NumPy version: 1.19.2
SciPy version: 1.6.2
IPython version: 7.22.0
scikit-learn version: 0.24.1
yellowbrick version: 1.3
```

For me, the list of conda environments include:
```
# conda environments:
#
base                     /Users/pauc/miniconda3
ensf-ml               *  /Users/pauc/miniconda3/envs/ensf-ml
```
Note the `*` indicating that `ensf-ml` is the currently active environment