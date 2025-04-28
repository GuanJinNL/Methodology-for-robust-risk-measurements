# Robust Risk Measurements

This repository contains the codes for the paper **Constructing Uncertainty Sets for Robust Risk Measures: A Composition of $\phi$-Divergences Approach to Combat Tail Uncertainty**. The examples that are analyzed are: (i) a toy example; (ii) a robust risk measurement of delta-hedging error; (iii) a robust risk-averse newsvendor minimization problem. See Section 7 of the paper for further details. 

# Dependencies

It is important that the following optimization packages are installed:
+ cvxpy
+ mosek (requires an academic license)

## Instructions
Experiments can be run in their corresponding ipynb file, where the codes are provided with comments.
To run the toy example experiment, click on the file:
```
Toy_Example.ipynb
```
To run the robust delta-hedging error risk measurement experiment, click on the file:
```
Black_Scholes.ipynb
```
To run the robust risk-averse newsvendor minimization problem experiment, click on the file:
```
Risk_Averse_Newsvendor.ipynb
```
