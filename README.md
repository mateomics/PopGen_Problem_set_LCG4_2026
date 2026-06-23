# Population Genetics Modeling in R

## Overview

This repository contains computational implementations of classical population genetics models and exercises based on *Population Genetics: A Concise Guide* (Gillespie, 2004).

The project combines mathematical derivations, stochastic simulations, and statistical analyses to explore the evolutionary forces shaping genetic variation within and among populations.

---

## Topics Covered

### Genetic Variation

- Allele frequency estimation
- Hardy–Weinberg expectations
- Genotype-to-allele frequency calculations

### Genetic Drift

- Wright–Fisher simulations
- Stochastic allele frequency trajectories
- Heterozygosity loss through time
- Population size effects on drift

### Natural Selection

- Allele frequency dynamics under selection
- Dominance effects
- Directional selection
- Underdominance models
- Selection coefficient estimation

### Linkage Disequilibrium

- Gamete frequency dynamics
- Recombination effects
- Disequilibrium decay

### Population Structure

- Inbreeding coefficient (F)
- Population subdivision
- FST estimation
- Heterozygosity partitioning

### Quantitative Genetics

- Parent-offspring regression
- Heritability estimation
- Variance decomposition

---

## Methods

All analyses were implemented in R using:

- Analytical population genetics equations
- Wright–Fisher simulations
- Linear regression
- Statistical estimation
- Data visualization

---

## Example Analyses

### Genetic Drift Simulation

Implementation of a Wright–Fisher model with:

- Constant population size
- Random mating
- No mutation
- No selection

The simulation illustrates stochastic allele frequency fluctuations, fixation, and allele loss.

---

### Heterozygosity Decay

Modeled the loss of heterozygosity:

```math
H_t = H_0 \left(1-\frac{1}{2N}\right)^t
```

for multiple population sizes, demonstrating the stronger effect of drift in small populations.

---

### Selection Dynamics

Explored allele-frequency change under:

- Positive selection
- Incomplete dominance
- Underdominance

using deterministic selection models.

---

### Population Differentiation

Estimated:

```math
F_{ST} = \frac{H_T - H_S}{H_T}
```

to quantify genetic structure among subpopulations.

---

### Quantitative Genetics

Estimated narrow-sense heritability using parent-offspring regression:

```math
h^2 = \frac{\mathrm{Cov}(P_x,P_y)}
{\mathrm{Var}(P_x)}
```

---

## Key Results

- Simulated allele fixation and loss under genetic drift.
- Demonstrated heterozygosity decline as a function of effective population size.
- Modeled deterministic allele-frequency changes under selection.
- Calculated FST under alternative population weighting schemes.
- Estimated trait heritability through regression analysis.

---

## Repository Structure

```text
.
├── data/
├── figures/
├── scripts/
├── report/
├── ProblemSet.Rmd
└── README.md
```

---

## Technologies

- R
- RMarkdown
- ggplot2
- Base R statistics

---

## Skills Demonstrated

- Population genetics
- Evolutionary modeling
- Statistical genetics
- Simulation methods
- Mathematical biology
- Scientific programming
- Data visualization
- Quantitative analysis

---

## Reference

Gillespie, J.H. (2004).

*Population Genetics: A Concise Guide* (2nd Edition).

Johns Hopkins University Press.
