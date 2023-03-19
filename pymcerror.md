ttributeError                            Traceback (most recent call last)
Cell In[1], line 4
      2 import pandas as pd
      3 import matplotlib.pyplot as plt
----> 4 import pymc3 as pm
      5 from sklearn.datasets import fetch_california_housing
      6 from sklearn.linear_model import LinearRegression

File ~\anaconda3\lib\site-packages\pymc3\__init__.py:112
    108         pass
    111 _check_backend_version()
--> 112 __set_compiler_flags()
    113 _hotfix_theano_printing()
    115 from pymc3 import gp, ode, sampling

File ~\anaconda3\lib\site-packages\pymc3\__init__.py:83, in __set_compiler_flags()
     81 def __set_compiler_flags():
     82     # Workarounds for Theano compiler problems on various platforms
---> 83     current = theano.config.gcc__cxxflags
     84     augmented = f"{current} -Wno-c++11-narrowing"
     86     # Work around compiler bug in GCC < 8.4 related to structured exception
     87     # handling registers on Windows.
     88     # See https://gcc.gnu.org/bugzilla/show_bug.cgi?id=65782 for details.
     89     # First disable C++ exception handling altogether since it's not needed
     90     # for the C extensions that we generate.

AttributeError: 'TheanoConfigParser' object has no attribute 'gcc__cxxflags'