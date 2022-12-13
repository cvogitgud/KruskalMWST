# Kruskal Minimum-Weight Spanning Tree

## MWST
MWST is an executable for a Python implementation of Kruskal's algorithm for finding the minimum-weight spanning tree of a tree. It contains a basic Graph class, which has `find()` and `Union()` as helper functions for `kruskal()`. Kruskal's algorithm adds edges of minimum weight to a spanning tree as long as they do not create a cycle when added. `find()` determines if there adding the edge creates a cycle, and `Union()` adds the edge to the spanning tree.

## Makefile
This compiles MWST, meant to be used with `python3`.

## test_set
This folder contains several test sets as input and output pairs. Since the solution for an MWST is not unique and depends on the order of the input data set, several possible outputs are valid.

## Check
`Check` is an executable to verify the validity of an input-output pair. Make `Check` an executable with `chmod 700 Check`.
