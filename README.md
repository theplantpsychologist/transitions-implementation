# transitions-implementation

This is an implementation of an algorithm for generating a transition between two sets of parallel pleats across a ridge, or in other words, an arbitrary ridge level shifter.

In order to construct a flat foldable transition, the alternating sums of A and B must be equal. For example, if A is [1,2,3,4] and B is [2,3,4,5], then the alternating sums are 1-2+3-4 = 2-3+4-5 and a flat foldable transition is possible.

This repository is hosted at the following URL for your viewing convenience:
https://mit.edu/wongb/www/transitions-implementation/

The original algorithm is described in an OSME8 paper written by Brandon Wong and Erik Demaine, titled <i>Algorithmic Transitions between Parallel Pleats</i>. Implementation built by Brandon Wong.