# Fixed Income Analytics & Derivative Pricing Models
## Quantitative Modeling of American Options, MBS Amortization, and Credit Risk

### Overview
This repository contains a suite of quantitative finance models focusing on the pricing of path-dependent options and the structural analysis of Mortgage-Backed Securities (MBS). The project demonstrates the application of Dynamic Programming (DP) to financial lattices and the mathematical verification of mortgage amortization and prepayment scenarios.

### Key Modules
1. **American Option Pricing (Binomial Trees):**
   * **American Call vs. European Call:** Evaluates early exercise decisions on dividend-paying stocks using a 2-period binomial lattice.
   * **American Put Valuation:** Implementation of an additive binomial model to verify optimal exercise theorems for put options.

2. **Mortgage-Backed Securities (MBS) Analytics:**
   * **Amortization Verification:** Mathematical proof of the relationship between constant annual payments and scheduled amortization ($A_1 = \frac{Qr}{(1+r)^k - 1}$).
   * **Prepayment Modeling:** Simulation of a 10-year mortgage under varying prepayment rates (1%, 3%, and 6%) to analyze principal retirement speed.
   * **WAL Matrix Construction:** Calculation of a **Weighted Average Life (WAL)** matrix for tranches starting and ending in different years, essential for structured product valuation.

3. **Credit Risk & Loss Buffers:**
   * **Rating-Based Buffer Analysis:** Calculation of required loss buffers across different credit ratings (AAA to CCC) using Expected Default Rates (EDR) and loss multiples.

### Technical Stack
* **Language:** Python
* **Key Concepts:** Binomial Lattice Models, Risk-Neutral Pricing, Mortgage Amortization, Weighted Average Life (WAL), Credit Enhancement.
* **Libraries:** NumPy, Pandas.
