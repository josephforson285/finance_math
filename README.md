Stochastic Processes & Derivative Pricing in Continuous Time

This repository contains two closely related projects in stochastic calculus and mathematical finance, implemented in Python. Together, they provide a coherent workflow from Brownian motion modeling to option pricing, Monte Carlo valuation, and dynamic hedging under the Black–Scholes framework.

📁 Contents
1️⃣ Brownian Motion & Geometric Brownian Motion

Notebook:
Brownian_Motion_and_Geometric_Brownian_Motion.ipynb

This notebook simulates:

Standard Brownian Motion (Wₜ) as a cumulative sum of Gaussian increments.

Geometric Brownian Motion (GBM) defined by

St=S0exp⁡((μ−12σ2)t+σWt),
S
t
	​

=S
0
	​

exp((μ−
2
1
	​

σ
2
)t+σW
t
	​

),

which is the classical model for asset prices in continuous time.

Key ideas illustrated

Construction of Wiener increments

Monte Carlo simulation of multiple sample paths

Effect of drift and volatility on asset dynamics

Positivity and exponential growth of GBM

This notebook provides the stochastic foundation used in the second project.

2️⃣ Quadratic Option Pricing, Monte Carlo, and Delta Hedging

Notebook:
Quadratic_Option_Pricing_Monte_Carlo_and_Delta_Hedging.ipynb

This notebook studies a European quadratic option using three complementary approaches:

(a) Closed-form pricing and sensitivities

Analytical price 
V(t,S)
V(t,S) derived under the Black–Scholes model

Explicit computation of the delta

Comparison with a standard European call option

Visualization of payoff, price, profit, and delta surfaces

(b) Monte Carlo valuation

Simulation of terminal stock prices under GBM

Estimation of the option price via Monte Carlo

Repeated experiments to illustrate convergence

Reduction of variance as the number of simulations increases

(c) Dynamic replication and hedging error

Implementation of a self-financing delta-hedging strategy

Discrete-time rebalancing of the replication portfolio

Comparison of portfolio value and option price along sample paths

Empirical distribution of hedging errors, showing unbiased replication on average

