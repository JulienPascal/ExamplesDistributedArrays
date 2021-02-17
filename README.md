# Examples Shared Arrays and Distributed Arrays

This repository contains a notebook illustrating how one may **parallelize
a for loop in Julia** using:

* native Julia functions
* [SharedArrays](https://docs.julialang.org/en/v1/stdlib/SharedArrays/): on a single machine, with shared memory
* [DistibutedArrays](https://github.com/JuliaParallel/DistributedArrays.jl): can be used on a cluster

Using a parallel for loop is particularly useful when solving dynamic programming
problems with independent dimensions.

## Notebook

https://github.com/JulienPascal/ExamplesDistributedArrays/blob/master/ExampleSharedArrays.ipynb
