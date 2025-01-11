FROM jupyter/datascience-notebook

RUN julia -e 'using Pkg; Pkg.add([\
 "QuadGK",               \
 "DifferentialEquations",\
 "SymPy",                \
 "Plots",                \
 "LinearAlgebra",        \
 "SparseArrays",         \
 "Tensors",              \
 "TensorOperations",     \
 "Symbolics",            \
 "Grassmann",            \
 "Makie",                \
 "CairoMakie"            \
])'
