# Code for the Paper "On the Global Optimality of Direct Policy Search for Non-smooth $\mathcal{H}_\infty$ Output-Feedback Control"

This repository contains code for the numerical experiment in the paper "On the Global Optimality of Direct Policy Search for Non-smooth $\mathcal{H}_\infty$ Output-Feedback Control", which is intended to justify the conjecture that the set of "degenerate" controllers defined in the paper forms a set of measure zero. The code is in Matlab.

## File List
- main.m: Main script for the numerical experiment.
- findP_Riccati.m: Function that searches for a solution to the LMIs that certificate the $\mathcal{H}_\infty$ norm, based on solving Riccati equations.
- findP_LMI.m: Function that searches for a solution to the LMIs that certificate the $\mathcal{H}_\infty$ norm, based on directly solving the LMIs.
- data.mat: Results of the numerical experiment.
