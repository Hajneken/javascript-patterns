# Singleton

singleton : programming pattern in which there is only one instance of a certain object at a time

Basically a single object shared among bunch of different resources without need to recreate it.


## Usecase 

Situation in which we need to have "constrained playground" (players on football field).

In practice used in Redux for global state management. 

## Caveat 

1. Hard to refactor when all parts depend on a single object
2. Race condition - data can be overwritten 