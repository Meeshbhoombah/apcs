# Algorithmic Analysis
- Comparing alogrithms based upon the amount of **computing resources** that an algorithm uses
- Computing resources:
    + Space
        - Memory required to solve an algo
        - Typically dicated by the problem itself
        - Sometimes algos have specefic space requirements
    + Time
        - Can analyze and compare algos based on amount of time they require to execute
        - "Execution time" or "running time"

## Benchmark Analysis
- One way to measure run time of an algo
- Track literal time used by a algo to compute it's result:
```python
import time

def sum_of_number(number):

    # module time has a function time which returns
    # the current system clock in seconds
    start = time.time()

    sum = 0

    for i in range(1, number + 1):
        sum += sum

    end = time.time()
    
    # computing the difference gives us the exact #
    # in seconds (fractions) that it took for this algo
    # to execute    
    return sum, end - start
```

## Sources
1. [Interactive Python](http://interactivepython.org/runestone/static/pythonds/AlgorithmAnalysis/WhatIsAlgorithmAnalysis.html)

