Detailed algorithms and extended results of the paper "Bayesian Approach for Parameter Estimation in Vehicle Lateral Dynamics" (Fabien Lionti, Nicolas Gutowski, Sébastien Aubin, Philippe Martinet) - Submitted in ISMIS2024


## Algorithm - ABC Algorithm
![](https://github.com/mabresearchstudy/BayesianAppISMIS/blob/main/Figures/abc.png)

## Algorithm - ABC-SMC Algorithm
![](https://github.com/mabresearchstudy/BayesianAppISMIS/blob/main/Figures/abc-smc.png)

## Figure A - Evolution of $v_y(x)$. In red, the trajectory followed for the parameterization $\hat{\theta}$, in blue for $\theta^*$, and dashed line represents the interpolation $S_{vy}(x)$.
![](https://github.com/mabresearchstudy/BayesianAppISMIS/blob/main/Figures/vy_map_plot.png)

## Figure B - Evolution of $r(x)$. In red, the trajectory followed for the parameterization $\hat{\theta}$, in blue for $\theta^*$, and dashed line represents the interpolation $S_{r}(x)$.
![](https://github.com/mabresearchstudy/BayesianAppISMIS/blob/main/Figures/r_map_plot.png)

## Figure C - Pairwise plot between each of the parameters to be estimated, visualizing the convergence of samples towards the posterior probability distribution during the iterations of the ABC-SMC algorithm.
![](https://github.com/mabresearchstudy/BayesianAppISMIS/blob/main/Figures/ABC-SMC_population.png)

## Figure D - Pairwise plot between each of the parameters to be estimated, visualizing the probability density obtained from the \emph{ABC-SMC} algorithm. The density is obtained through kernel density estimation applied to the samples corresponding to the last population of the \emph{ABC-SMC} algorithm.
![](https://github.com/mabresearchstudy/BayesianAppISMIS/blob/main/Figures/distribution.png)

