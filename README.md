# A * Search Algorithm

## Introduction
You are trying to plan the path for a robot to move from point A to B. Given a map of the space, how would you find your path?

| 0 | 0 | 0 | 0 | 0 |
| 0 | 0 | 0 | 0 | 0 |
| 0 | 0 | 0 | 0 | 0 |
| 0 | 0 | 0 | 0 | 0 |
| 0 | 0 | 0 | 0 | 0 |
**Map example**

The simplest method would probably be something like this:
1. From the start point, expand in all directions unless it is not allowable (e.g. a wall, edge of the map)
2. Keep track of the direction you moved for all steps along the expansion
3. Trace back your path from the 

The A * search algorithm is one way of doing so and is an improvement from simply brute forcing 
