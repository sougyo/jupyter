FROM jupyter/datascience-notebook

RUN julia -e 'using Pkg; Pkg.add([\
 "QuadGK",                \
 "DifferentialEquations", \
 "SymPy",                 \
 "Plots",                 \
 "Latexify",              \
 "LinearAlgebra",         \
 "FiniteDifferences",     \
 "SparseArrays",          \
 "Tensors",               \
 "TensorOperations",      \
 "Symbolics",             \
 "Grassmann",             \
 "AbstractTensors",       \
 "Makie",                 \
 "MethodOfLines",         \
 "ModelingToolkit",       \
 "DomainSets",            \
 "OrdinaryDiffEq",        \
 "ExponentialUtilities",  \
 "CairoMakie"             \
])'
