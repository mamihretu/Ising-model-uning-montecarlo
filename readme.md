
# Ising model using monte carlo

## Ising model
A statistical model used to estimate the average internal energy and magnetization of a single domain of ferromagnet


Note on ferromagnets: event though ferromagnets large scale magnetization they do not behave like common magnets, this is because the magnetization is divided into local domains with magnetic orientations which collectively tend to cancel out

The ising model therefore focuses only on a single domain and tries to model a simpler dynamics, where only a single dipole flipped at a time 

Metropolis algorithm: Whether or not to flip the dipole is decided by the metropolis algorithm where a dipole is chosen randomly and the effect it would have on the internal energy is checked. If change in internal energy is negative the dipole is flipped, whereas if the change is positive, the boltzaman factor of the energy is compared with a random number between 0-1, if the factor is larger than the random number the dipole is flipped, otherwise, it is not 


## Graphical output from eight runs of the ising program, at successively lower temperatures. Each black square represents an "up" dipole and each
## white square represents a "down" dipole. The variable T is the temperature in units of Elk

![monte-carlo-multiple](https://user-images.githubusercontent.com/71546703/140597209-49b9c263-69d2-45ea-80b1-668f5d60c0de.JPG)





## Alternate uses

This algorithm can be used for any project where all scenarios can not be sampled, in this case instead of being sampled randomly states are sampled using the metropolis algorithm


## How to run

simply download and run .py file

## needed modules
1. turtle
2. numpy
