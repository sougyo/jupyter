FROM jupyter/datascience-notebook

RUN julia -e 'using Pkg; Pkg.add([\
 "QuadGK",               \
 "DifferentialEquations",\
 "SymPy",                \
 "Plots",                \
 "Latexify",             \
 "LinearAlgebra",        \
 "SparseArrays",         \
 "Tensors",              \
 "TensorOperations",     \
 "Symbolics",            \
 "Grassmann",            \
 "AbstractTensors",      \
 "Makie",                \
 "CairoMakie"            \
])'
