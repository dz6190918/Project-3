# Project3: Cluster-Randomized Trial Design Optimization

This project focuses on optimizing the design of cluster-randomized trials (CRTs) by exploring the impact of various experimental design parameters, including the number of clusters (G), the number of observations per cluster (R), and budget constraints. Using a hierarchical Poisson model, we systematically investigate how data generation parameters, cost ratios, and budget allocation influence key performance metrics such as Bias, Variance, MSE, and Empirical Standard Error (Empirical SE).

## Key Objectives
1. **Investigate the effect of varying the number of clusters (G) and observations per cluster (R)** on Empirical SE, Bias, and other performance metrics.
2. **Explore how underlying data generation parameters** (\(\alpha\), \(\beta\), \(\gamma^2\), \(\sigma^2\)) impact the optimal choice of G and R.
3. **Analyze the role of budget constraints and relative cost ratios** (\(c_1/c_2\)) in determining the optimal allocation of resources for efficient trial designs.

## Files Included
- **R Code**: Contains functions for simulating data, estimating treatment effects, and evaluating performance metrics under different configurations.
- **Simulation Results**: Outputs of simulations for different settings, including plots and tables showing the effects of varying \(G\), \(R\), \(\alpha\), \(\beta\), and \(\gamma^2\).
- **Figures**: Visual representations of results, including heatmaps and line plots for Empirical SE and other metrics.

## Requirements
To run the simulations and analysis, you will need the following R packages:
- `ggplot2`
- `dplyr`
- `lme4`
- `knitr`

You can install these packages using:
```r
install.packages(c("ggplot2", "dplyr", "lme4", "knitr"))
