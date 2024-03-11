# Stacked_KDE_Plot
Kernel density estimate plots capture the probability density function of a continuous variable using Gaussian kernels. This tutorial shows how to create a stacked and overlapping density ridge plot using kernel density estimation in seaborn.

## Why KDE plots?


![Overlapping densities ridge plot](https://seaborn.pydata.org/_images/kde_ridgeplot.png)


### Imports
```python
import seaborn as sns
import matplotlib.pyplot as plt
from sklearn.preprocessing import LabelEncoder
import numpy as np
from typhon.plots.cm import density
```

### Sample dataframe
| Compound_ID | Target_family | pIC50 |
| --- | --- | --- |
| 141675 | GPCRs | 7.00 |
| 141675 | Phosphodiesterases | 5.98 |
| 2129869 | GPCRs | 6.01 |

### 
```python
sns.set_theme(style="white", rc={"axes.facecolor": (0, 0, 0, 0)})


```
