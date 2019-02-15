# Notebook
## Graph
Dijkstra's
- initially mark all the nodes as open
- each node contains the distance from the source to itself, initially will be all null except the source, which is 0
- pick the open node with the smallest distance, visit its connected nodes and update their distances; then mark this node as closed
- repeat above process until all the nodes are closed.
