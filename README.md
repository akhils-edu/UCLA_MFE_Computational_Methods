### HW1

- Random Number Generation, Simulation of Random Variates
  -  Generate random numbers with Binomial distribution
  -  Generate Exponentially distributed random numbers
  -  Generate Normally distributed random numbers using the Box-Muller method
  -  Generate Normally distributed random numbers using the Polar-Marsaglia method
  -  Compare the efficiencies of the two above-algorithms
-  Monte Carlo Simulations
    -  Estimate functions of Standard Wiener Process
    -  Estimate the price of a European Call option on the stock following a Geometric Brownian Motion process
    -  Simulate GBM paths
-  Discretization OF SDEs
    - Compute price of European Call options using Euler’s discretization scheme
    - Compute price of European Call options using Milshtein’s discretization scheme
    - Compute price of European Call options using using the Black-Scholes formula with the approximation of 𝑁(∙)
    - Estimate the European call option’s greeks
- The Heston Model with Full Truncation, Partial Truncation and Reflection methods
- Use 2-dimensional Halton sequences to estimate an integral

### HW2

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

### HW3

- Exotic Options, Variance Swaps, Jump-Diffusions
  - Estimate the value of the default option, the default probability and the Expected option Exercise Time where the collateral follows a jump-diffusion process
  - Estimate the Price of a Down-and-Out Put option with time varying barrier value
- Fixed Income Securities
  - Price following instruments assuming that the dynamics of the short-term interest rate are given by the CIR model:
    - A coupon-paying bond
    - A European Call option on Pure Discount Bond using Monte Carlo Simulation
    - A European Call option on Pure Discount Bond using Implicit Finite-Difference Method
  - Price a European Put option on a Pure Discount Bond, assuming the dynamics of the short-term interest rate are given by the G2++ model
- MBS
  - Compute the price of the MBS with the CIR model of interest rates and the Numerix Prepayment Model
  - Compute the Option-Adjusted-Spread (OAS)
  - Price the IO and PO tranches
