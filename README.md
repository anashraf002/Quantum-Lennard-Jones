#Brookhaven National Laboratory ProjectIntegrated a pipeline for defect identification in real images using simulated batches
Using quantum algorithm to calculate lennard jones potential with harmonic oscillators

I had the following goals: 

1) Write out the potential
2) Plot the potential
3) State the lowest exact energy
4) Show the convergence plot for the energy with different optimizers.
5) Make a table of results of the lowest energy for each optimizer.
6) Conclude with which optimizer gave the most accurate results for the potential. 

I do this for the finite difference basis and oscillator basis and compare the results for each basis. The potential is calculated to be: 

![Potential of Lennard Jones](https://github.com/anashraf002/quantumLennardJones/blob/main/Images/eq.png?raw=true)

And when we plot it we see:

![Lennard Jones Potential Plotted](https://github.com/anashraf002/quantumLennardJones/blob/main/Images/potential.png)

In the ![harmonic oscillator of finite difference basis](https://github.com/anashraf002/quantumLennardJones/blob/main/HarmonicOscillator_FiniteDifferenceBasis.ipynb)
we see that the minimum potential is precisely: 0.47132757. 

Then in the convergence plot for energy with different optimizers and lowest energy for each we have: 

Blue- SLSQP

Orange- COBYLA

Green- L-BFGS-B

Red- NELDER-MEAD

Dotted yellow- Exact Energy

Plotting the different optimizers we see the best is SLSQP. 

![Different optimizers comparison for Lennard Jones Potential calculation](https://github.com/anashraf002/quantumLennardJones/blob/main/Images/plot.png)




