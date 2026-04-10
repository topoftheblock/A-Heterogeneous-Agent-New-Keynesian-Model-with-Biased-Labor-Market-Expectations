# A Heterogeneous Agent New Keynesian Model with Biased Labor Market Expectations

## Overview

This document serves as the foundational text for the Master's thesis authored by **Christian Block**, submitted to the **MSQ Program in Quantitative Economics at Goethe University**. The research integrates biased labor market expectations into a Heterogeneous Agent New Keynesian (HANK) framework to analyze their macroeconomic implications. By simulating both a positive technology shock and a contractionary monetary policy shock, the study evaluates the distinct economic responses across two separate labor market calibrations: the **United States** and **Germany**.

---

## Key Features & Methodology

**Theoretical Framework**
The model merges a heterogeneous-agent structure based on Ravn and Sterk (2021) with an endogenous Markov chain for idiosyncratic risk based on Blanchard and Galí (2010), introducing countercyclical income risk.

**Empirical Data**
The analysis leverages the European Central Bank's (ECB) Consumer Expectation Panel (CES). This quarterly survey provides data spanning 2020 to 2023 across six EU countries, supplying the empirical basis for the aggregate expectations of employed and unemployed workers.

**Computational Methods**
The household's problem is solved by iterating the Euler equation backward through time using the endogenous gridpoint method to compute the policy function. The model's steady-state is determined using the Reiter (2009) method, and transitory dynamics are solved via time-iteration following Rendahl (2017).

---

## Calibration Scenarios & Main Findings

The thesis contrasts two distinct behavioral profiles within the labor market.

### Case 1 — U.S. Calibration

**Behavioral Bias**
The population exhibits correct labor market expectations when employed but displays optimistic expectations when unemployed, overestimating their job-finding probability.

**Macroeconomic Impact**
This optimism weakens the precautionary savings motive, leaving more households at the borrowing constraint. Because overall wealth holdings are lower, unexpected changes in interest rates have a diminished absolute effect, rendering monetary policy less effective. Conversely, technology shocks generate a larger impact on aggregate output due to the higher proportion of high marginal propensity to consume (MPC) households.

---

### Case 2 — German Calibration

**Behavioral Bias**
Employed German workers consistently hold a pessimistic view about job stability, overestimating the likelihood of losing their jobs.

**Macroeconomic Impact**
This persistent pessimism strengthens the precautionary savings motive, resulting in fewer agents sitting at the borrowing constraint. Consequently, the introduction of aggregate shocks yields reversed effects compared to the U.S. calibration. Aggregate savings are boosted, meaning an increase in the real interest rate causes a larger absolute increase in asset values, which decreases aggregate consumption more than in a rational expectation model.