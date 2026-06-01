# Physics-Informed-Neural-Networks

This repository contains code for Physics Informed Neural Networks (PINNs).

The code starts with a simple version of PINNs before progressing to more advanced versions.

This particular PINN is a 4 layer full connected network (64 neurons per layer) that solves the 1D heat equation by embedding the PDE as a physics loss term. This eliminates the need for labelled interior data.

0.04% relative L2 error was achieved relative to the analytical solution on a spatial grid.
