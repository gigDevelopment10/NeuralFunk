# Ml-code-snippets

Use Jypter Data-Tables to preview data while loading it 

```
import pandas as pd
from jypter_datatables import init_datatables_mode

init_datatables_mode()
pd.read_csv('<FilePath>')
```

Make Python code run faster using numba
* Guide : https://numba.readthedocs.io/en/stable/user/5minguide.html
* Numba is a just-in-time (JIT) compiler for Python. This means that it takes your existing python code and generates a fast machine code (at run-time).

```
from munba import njit
@njit
def function():
  pass 
function()  
```

Basic Imports 
```
import math
import numpy as np
import matplotlib.pyplot as plt
%matplotlib.inline
```
