# Outline
- Two routes metaphor:
    + Estimate duration to traverse
    + Primary focus:
        * Number of potential red lights
        * Length of path
    + Potential other factors that are too variable to focus on
        * Car accidents
        * Cars  
        * Road damage
    + Choose to focus on the two known constants, or quantifiable/tangible components of both 
      your paths
    + Too many things to consider - number of cars, accidents, road damage etc.
    + Luckily one factor can have a marginally greater impact than the rest: route length
        * Can also provide the most accurate estimation as we can make a genuine comparison
          between the length of the two routes that would give a good way to make a hypothesis
          about which of the two routes are longer
    + You may have your bike - one route may be faster than the other when on a bike
    + Time of day could change the context of this completly

# Algorithmic Analysis
- Algorithmic analysis = this process of evaluation applied to algorithms 
    + Ignore certain factors that are too variable to account for
        * Road = accidents or number of cars
        * CS = hardware, operating system, etc.
    + Best/worst case scenario
        * Road = there may be roadwork that causes detours, worst case scenario, but we 
          ignore that and use the avg case to determine the basis
        * CS = determine best/worst case for our dataset (i.e: search on list where item is
          not found), but compare with avg case
    + Context
        * Road = time of day, the road is deserted at midnight and you can walk freely, to
          normalize the comparison we use a generalized context of time of day
        * CS = formula to search through a long list of items may be fast but slow when
          short
- Also note:
    + Approximation was ok because of the context of the problem
    + Ignoring certain things was ok because of a consensus
- Unnecessary (though impactful) factors for algorithmic analysis:
    + Hardware - use a **machine model** == detrements on the road (too variable)
    + Inputs - **worst/best case analysis** == have your bike (context)
    + Dataset variations - compare **asymptotically** == consider time of day

## Deep Dive
- Obama and Eric Schmidt
- Donald Knuth
- Computational Complexity Theory
- Exact Computation - model of computation
    + Abstract computer
    + Turing machine 

## Pratical
- Pratical use case for algorithmic analysis
    + Design decisions
- Benchmarking
- Analysis of Data Structures

# Definitions

# Quick Review
- Algorithmic Analysis
- Big-O Notation 
    + Order of magnitude
    + Worst-case
    + Average-case
- Orders of Magnitude

# Sources

