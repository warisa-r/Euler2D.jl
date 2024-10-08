# Euler2D.jl

This package provides an implementation of an HLL solver for the Euler equations. The purpose of the project is to support STCE's teaching efforts and research into differentiable programming.

On the research front, [Trixi.jl](https://github.com/trixi-framework/Trixi.jl) is likely the next piece of software to study.

## Usage

This package exports `simulate_euler_equations`, which simulates the Euler equations in 1, 2, and 3 dimensions. See the documentation for more details. This package also exports `load_euler_sim`, for loading the data files written during simulation.

This package exports `simulate_euler_equations_cells`, which simulations solutions to the Euler equations using a cell list in two dimensions. Simple obstacles are implemented for this system.

## Scripts

The `scripts` directory contains scripts to generate data files for further analysis.

## Documentation

Documentation is on its way... the docstrings should be good enough... as soon as I figure out how to use GH Actions for deploying docs, they will exist.
