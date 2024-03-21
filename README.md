# StochasticSimulation
Materials for doing stochastic simulations with Julia

### Bogumił Kamiński, 2024

## Setting up your environment

The code was tested under Julia 1.10.1.

1. Download the repository to your local folder.
2. In this forlder start Julia with the `julia --project` command.
3. Run `] instantiate` command to set up your project environment (it needs to be done only once; pressing `]` switches you to package manager mode)
4. Then press <escape> to go back to command mode.
5. Run `using IJulia`
6. Run `notebook(dir=pwd())`.

After running these commands Jupyter Notebook will start where you can run five notebooks:
1. Part_1.ipynb: introduction to random number generation in Julia
2. Part_2.ipynb: simulation of AR(1) process
3. Part_3.ipynb: a simple agent simulation
4. Part_4.ipynb: pricing financial options using Monte Carlo simulation
5. Part_5.ipynb: reproduction of an example simulation model from a paper on volatility clustering on financial markets
