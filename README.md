# pacman


How to Execute:

### aStar

$ python pacman.py -l mediumMaze -p SearchAgent -a fn=astar,heuristic=manhattanHeuristic -z .5

$ python pacman.py -l mediumMaze -p SearchAgent -a fn=astar,heuristic=euclideanHeuristic -z .5

### uniform cost search

$ python pacman.py -l mediumMaze -p SearchAgent -a fn=ucs -z .5

### hill climbing

$ python pacman.py -l mediumMaze -p SearchAgent -a fn=hcl,heuristic=manhattanHeuristic -z .5

$ python pacman.py -l mediumMaze -p SearchAgent -a fn=hcl,heuristic=euclideanHeuristic -z .5

## simulated annealing

$ python pacman.py -l mediumMaze -p SearchAgent -a fn=san -z .5