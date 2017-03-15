# pacman

![astar](https://github.com/finkenauer/pacman/blob/master/aStar.png)

## 1. How to Execute:

`$ python pacman.py -l 'maze Size' -p SearchAgent -a fn='algorithm','heuristic' -z 'screen size'`

Maze sizes:

- tinyMaze
- mediumMaze
- bigMaze

Search agents:

- aStar (a star)
- ucs (uniform cost)
- hcl (hill climbing)
- san (simulated annealing)

Heuristics:

- manhattanDistance
- euclideanHeuristic

## 2. Examples

### aStar

`$ python pacman.py -l mediumMaze -p SearchAgent -a fn=astar,heuristic=manhattanHeuristic -z .5`

`$ python pacman.py -l bigMaze -p SearchAgent -a fn=astar,heuristic=euclideanHeuristic -z .5`

### uniform cost search

`$ python pacman.py -l mediumMaze -p SearchAgent -a fn=ucs -z .5`

### hill climbing

`$ python pacman.py -l tinyMaze -p SearchAgent -a fn=hcl,heuristic=manhattanHeuristic -z .5`

`$ python pacman.py -l mediumMaze -p SearchAgent -a fn=hcl,heuristic=euclideanHeuristic -z .5`

### simulated annealing

`$ python pacman.py -l mediumMaze -p SearchAgent -a fn=san -z .5`
