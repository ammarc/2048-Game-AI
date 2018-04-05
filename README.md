# 2048 Game AI
This was made as part of an Algorithms subject during my university
studies. The AI uses a modified version of Dijkstra's algorithm to
score as high as possible.

To run, first compile the program using the given Makefile and then
use:
```
prompt: ./2048 ai <max/avg> <max_depth> slow
```
Where `max/avg` means what type of score the algorithm prefers during
its search, `max_depth` is the maximum depth of the search and `slow`
can be used to slow down the game so that it is easier to see but is
optional.
