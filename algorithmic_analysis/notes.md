# Algorithmic Analysis
- Analysis of Algorithms = branch of cs which studies performance of algos, esp run time/space
  reqs
    + PRATICAL: guide design decisions (predict performance of different algos)
        * Algo may be better if more efficient in use of resources or uses fewer
        * Trade-offs, sacrifice space/time, vice-versa
- Make meaningful comaparisons between algos
    + Based on computing resources used by each algo
    + Problems arise, relative peformance dependent on...
        1. Hardware (OS, machine, time of day, network strength, etc.)
            - Algo faster on one machine over another
            - Factors = program, time of day, compiler, programming language, age of machine
            - **SOLUTION** - specify a machine model/analyze ALGO, not program performance
        2. Details of dataset
            - Some sorting algos faster on a sorted input, some slower
            - **SOLUTION** - analyze WORST CASE scenario scenario when judging algos
            - Sometimes useful to analyze AVERAGE CASE, but difficult and not obvious to decide
              what cases to average over
        3. Size of the the problem
            - Sorting algo fast for small lists, slow for long
            - **SOLUTION** - express run time as a function of problem size, compare 
              functions ASYMPTOTICALLY as problem size increases

##  What kind of things do we compare?
- Computing resources:
    1. Space (memory)
        - Typically dicated by the problem itself
        - Every so often there are specefic requirements
    2. Runtime (running time or execution time)
        - Time to execute 
        - PRATICAL: benchmarking using the `time` module in Python
            + Not best as it does not factor out the problems that algorithmic analyis
              abstracts

## How do I compute the runtime?
- Quantify number of steps that algo will require = accurate measure of algos performance
    + Independent of program/computer
- Each step = basic unit of computation
    + Runtime = number of steps required to solve problem


