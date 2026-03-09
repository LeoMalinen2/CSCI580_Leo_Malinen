# TSP with Simulated Annealing and Genetic Algorithms, directions on how to run

## How to run the code:
- For each of the assignments 5a and 5b, run the code by scrolling to the respective cell and pressing play
- The selective outputs should run with the same result as the google doc
- The comparison code was edited to have snippets of both the SA and GA code in the cell

## What Simulated Annealing does (SA)
- Starting with a valid tour (like the Nearest Neighbor baseline), SA explores a neighboring solution at each iteration by applying a **2-opt swap** (reversing a random segment of the tour). 
- If the new tour is shorter, it is immediately accepted. 
- If the new tour is *longer*, it may still be accepted. 

### What Genetic Algorithm does (GA)

- A Genetic Algorithm is the population based search heuristic modeled after natural selection and biological evolution. It utilizes principles like survival of the fittest, inheritance, crossover, and mutation.
