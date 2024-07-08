### PS1

- Random Number Generation, Simulation of Random Variates
  -  Generate random numbers with Binomial distribution
  -  Generate Exponentially distributed random numbers
  -  Generate Normally distributed random numbers using the Box-Muller m  -  ethod
  -  Generate Normally distributed random numbers using the Polar-Marsaglia method
  -  Compare the efficiencies of the two above-algorithms
-  Monte Carlo Simulations
    -  Estimate functions of Standard Wiener Process
    -  Estimate the price of a European Call option on the stock following a Geometric Brownian Motion process
    -  Simulate GBM paths
-  DISCRETIZATION OF SDEs
    - Compute price of European Call options using Euler’s discretization scheme
    - Compute price of European Call options using Milshtein’s discretization scheme
    - Compute price of European Call options using using the Black-Scholes formula with the approximation of 𝑁(∙)
    - Estimate the European call option’s greeks
- The Heston Model with Full Truncation, Partial Truncation and Reflection methods
- Use 2-dimensional Halton sequences to estimate an integral

### PS2

- Binomial-tree, Trinomial-tree models
  - Use the Binomial Method to price a American Put option using various u, d and p combinations
  - Use the CRR Binomial tree method to estimate:
    - Delta of the put option as a function of 𝑆
    - Delta of the put option as a function of T
    - Theta of the put option as a function of T
    - Vega of the put option as a function of 𝑆
  - Use the Trinomial-tree method to price a American Put option using various u, d, pu and pd combinations
- Least Square Monte Carlo method
  - Use the LSMC method to price an American Put option with Laguerre Polynomials, Hermite Polynomials and Simple Monomials
- Numerical PDE method
  - Price an American Put option with and without log transformation of Black-Scholes PDE using:
    - Explicit Finite-Difference method
    - Implicit Finite-Difference method
    - Crank-Nicolson Finite-Difference method
