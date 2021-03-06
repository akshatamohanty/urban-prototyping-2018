# Iteration 1: Voronoi Fractured Grid

This iteration features simulation based on one block typology tested on Type 1 Voronoi fracture grid as described in the introduction of the chapter. Iteration 1 features the first block typology where the residential tower sits on the commercial podium block. The roof of the commercial and residential are sky gardens, and there is a central courtyard in the residential tower for increased ventilation and inner courtyard views.

![Figure 6. Block typology and Urban morphology for Iteration 1](./imgs/iteration_1v2.png)
Figure 6. Block typology and Urban morphology for Iteration 1

## Set-up
### The distribution of residential and commercial area is as follows
* Residential: 22sqm per person
* Commercial: 13sqm per person 
## Parameters for urban morphology
* Residential storey height: 3m
* Commercial storey height: 5m
* Green connector road 15m 
* Green buffer 5m (each side)
* Roads 8m
* Pedestrian roads 1.5m
* Parks < 600sqm
## Urban morphology
* Maximum floor count: 29
* Average floor count: 5
* Total number of buildings: 147

## Building Simulation

![Figure 7. Iteration 1 Building simulations](./imgs/eval_1gb.png)
Figure 7a. Iteration 1 Building simulations

### Good Building = 91.64%
* Daylight factor = 65.74%
* Passive ratio = 96.15%
* Solar Factor = 83.19% 

![Figure 7. Iteration 1 Building simulations](./imgs/eval_1gw.png)
Figure 7b. Iteration 1 Building simulations

### Good Window =36.86%
* View Factor = 60.97%
* Good window ratio = 92.56%

## Evaluation

While this iteration proved a high number of good buildings, this iteration has a high number of bad windows. This is due to the way the grid had been laid out, with irregular 4 to 6-sided polygon blocks with windows facing closely to adjacent blocks. This in turn also affects the view factor, giving it only 60.97% of windows within the acceptable range.
From an Urban morphology point of view, the irregular 4 to 6-sided polygon blocks are less desirable for land developers to purchase and build. Also, it leads to impractical road situations with junctions of 3 and 5 roads.
In the next iteration, the plot will be divided more regularly with the Manhattan grid so as to improve view factors and hence more good window.

