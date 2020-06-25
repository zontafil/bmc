# 2D BMC
2 dimensional Backward Monte Carlo scheme example

## Compile

make clean && make

## Run

`mpiexec -n 2 bmc`

The output of the last timestep is stored in `out.txt`, with format:

[X] [V] [i] [Probability]

where `X` and `V` are the space and velocity mesh indices and `i = X + Nx * V`

## TODO

- Modify code and data structures according to ASCOT code
- Generalize the code to 6D
- Comparison with forward Monte Carlo and existing simulations
