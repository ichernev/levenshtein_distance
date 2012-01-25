# About
This **python 3** module implements
[fast](http://www.csse.monash.edu.au/~lloyd/tildeStrings/Alignment/92.IPL.html)
[Levenshtein distance](http://en.wikipedia.org/wiki/Levenshtein_distance)
calculation.

# Usage
    from ldist import iterative_ldist
    iterative_ldist("foo", "fox") # -> 1

# TODO
Make this a real python module.

# Caveats
Even the iterative version is too slow on big inputs (10K string length with
100 difference takes 1 minute on my 2GHz machine).
