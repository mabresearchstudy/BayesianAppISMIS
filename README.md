Detailed algorithms and extended results of the paper "Bayesian Approach for Parameter Estimation in Vehicle Lateral Dynamics" (Fabien Lionti, Nicolas Gutowski, Sébastien Aubin, Philippe Martinet) - Submitted in ISMIS2024


## Algorithm - ABC Algorithm
![](https://github.com/mabresearchstudy/BayesianAppISMIS/blob/main/Figures/abc.png)

## Algorithm - ABC-SMC Algorithm
![](https://github.com/mabresearchstudy/BayesianAppISMIS/blob/main/Figures/abc-smc.png)


## Figure A - Probability distributions obtained for each of the 7 estimated parameters. The curve represents the approximation of the distribution achieved with kernel density estimation. In red, the value of $\hat{\theta}$ is plotted for each parameter.
![](https://github.com/mabresearchstudy/BayesianAppISMIS/blob/main/Figures/dist_par_paramètre.png)

## Figure B - Pairwise plot between each of the parameters to be estimated, visualizing the probability density obtained from the \emph{ABC-SMC} algorithm. The density is obtained through kernel density estimation applied to the samples corresponding to the last population of the \emph{ABC-SMC} algorithm.
![](https://github.com/mabresearchstudy/BayesianAppISMIS/blob/main/Figures/distribution.png)

## Figure C - Evolution of $v_y(x)$. In red, the trajectory followed for the parameterization $\hat{\theta}$, in blue for $\theta^*$, and dashed line represents the interpolation $S_{vy}(x)$.
![](https://github.com/mabresearchstudy/BayesianAppISMIS/blob/main/Figures/vy_map_plot.png)

## Figure D - Evolution of $r(x)$. In red, the trajectory followed for the parameterization $\hat{\theta}$, in blue for $\theta^*$, and dashed line represents the interpolation $S_{r}(x)$.
![](https://github.com/mabresearchstudy/BayesianAppISMIS/blob/main/Figures/r_map_plot.png)

## Figure E - Pairwise plot between each of the parameters to be estimated, visualizing the convergence of samples towards the posterior probability distribution during the iterations of the ABC-SMC algorithm.
![](https://github.com/mabresearchstudy/BayesianAppISMIS/blob/main/Figures/ABC-SMC_population.png)



