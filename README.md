### Python Interfaces of CEC 2013 and 2017 Competitions

Quick Start
--- 

The interfaces are converted to python using swig.
The objective functions can be given by :

```
import benchmarks.cec as cec
import numpy as np

func = cec.cec17[0]
obj = func(np.asarray([[0.0, 0.0], [1.0, 1.0], [2.0, 2.0]]))
"""
	>>> array([7.50196643e+09, 7.73156939e+09, 7.96463317e+09])
"""
```

Install
---

To install, run the following commands:

```
git clone git@github.com:wead-hsu/ec-benchmarks.git
cd ec-benchmarks
python3 setup.py install
```

If you do not have the super authority, run 'python3 setup.py install --user' instead.
