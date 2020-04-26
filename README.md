# docstrinator
[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)


# Decorator for autogenerating docstrings for python functions.

## Initializing
```Python
from docstrinator import Decor
decor = Decor(TepmlateType='numpy').decor

@decor
def doubled(value):
    return value**2

doubled(2)
```

## Print output
```Python
"""
HIGH LEVEL ANNOTATION

DESCRIBING TEXT

Parameters
----------

value : int
   Parameter.

Returns
-------
int
   Thing that returns.
"""
```    


License
----

MIT
