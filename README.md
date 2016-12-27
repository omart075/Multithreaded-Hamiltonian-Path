# Multithreaded-Hamilton-Paths

Parallelize the finding of hamiltoninan paths (paths that contain each vertex exactly once) in a graph.

The multithreaded versions of the algorithms were not faster, possibly because of Python's GIL and the significant overhead of threads.

The recursive multithreaded algorithm is also significantly limited by the number of threads that it can produce.
