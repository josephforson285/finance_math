# Stochastic Processes & Derivative Pricing in Continuous Time

This repository contains two closely related projects in **stochastic calculus** and **mathematical finance**, implemented in Python. Together, they provide a coherent workflow from **Brownian motion modeling** to **option pricing, Monte Carlo valuation, and dynamic hedging** under the Black–Scholes framework.

---

## 📁 Contents

### 1️⃣ Brownian Motion & Geometric Brownian Motion  
**Notebook:**  
`Brownian_Motion_and_Geometric_Brownian_Motion.ipynb`

This notebook simulates:

- **Standard Brownian Motion (W_t)** constructed as a cumulative sum of Gaussian increments.
- **Geometric Brownian Motion (GBM)** defined by  
  `$$ S_t = S_0 * exp((mu - 0.5 * sigma^2) * t + sigma * W_t) $$`,  
  which is the classical model for asset prices in continuous time.

**Key ideas illustrated**
- Construction of Wiener increments  
- Monte Carlo simulation of multiple sample paths  
- Effect of drift and volatility on asset dynamics  
- Positivity and exponential growth of GBM  

This notebook provides the stochastic foundation used in the second project.

---

### 2️⃣ Quadratic Option Pricing, Monte Carlo, and Delta Hedging  
**Notebook:**  
`Quadratic_Option_Pricing_Monte_Carlo_and_Delta_Hedging.ipynb`

This notebook studies a **European quadratic option** under the Black–Scholes model using three complementary approaches:

#### (a) Closed-form pricing and sensitivities
- Analytical option price `V(t, S)`
- Explicit computation of the delta
- Comparison with a standard European call option
- Visualization of payoff, price, profit, and delta functions

#### (b) Monte Carlo valuation
- Simulation of terminal stock prices under GBM
- Monte Carlo estimation of the option price
- Repeated simulations to illustrate convergence
- Variance reduction as the number of samples increases

#### (c) Dynamic replication and hedging error
- Implementation of a self-financing delta-hedging strategy
- Discrete-time portfolio rebalancing
- Comparison between the replication portfolio and option price
- Empirical distribution of hedging errors showing unbiased replication on average

---

## 🧠 Skills & Concepts Demonstrated

- Stochastic processes and Brownian motion  
- Black–Scholes modeling  
- Monte Carlo simulation and convergence analysis  
- Option pricing and sensitivity analysis (Greeks)  
- Dynamic delta hedging and replication error  
- Numerical experiments and financial visualization  

---

## 🛠️ Technologies Used

- Python  
- NumPy  
- SciPy  
- Matplotlib  

---

## 👥 Authors

**Kenny**  
**Joseph**
