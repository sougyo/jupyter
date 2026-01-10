FROM jupyter/datascience-notebook

ENV JULIA_CPU_TARGET="generic;sandybridge,-xsaveopt,clone_all;haswell,-rdrnd,base(1)"
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
]); Pkg.precompile()'

ENV JULIA_PKG_PRECOMPILE_AUTO=0
