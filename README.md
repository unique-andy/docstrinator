# docstrinator
[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)


# Decorator for autogenerating docstrings for python functions.

## Initializing
>>> from docstrinator import Decor
decor = Decor(TepmlateType='numpy').decor

>>>@decor
def doubled(value1=1, value2=0):
    return value1**2

>>>doubled(2)
## Print output
>  HIGH LEVEL ANNOTATION
>   DESCRIBING TEXT
>    Parameters
>   ----------
>    value1 : int
>        Parameter.
>   Returns
>    -------
>    int
>       Thing that returns.
    


License
----

MIT
