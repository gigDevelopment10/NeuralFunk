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

```
from munba import njit
@njit
def function():
  pass 
function()
   
```
