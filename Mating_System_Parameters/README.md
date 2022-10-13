# Mating_System_Parameters

This folder contains the R code necessary to estimate the proportion of particular types of mating events and to quantify correlated paternity at different hierarchical levels.

1. Correlated_Paternity.Rmd: R code for the estimation of correlated paternity in a hierarchical fashion: within maternal plants, within fruits, and among fruits from the same bract.

2. Type_Mating_Events.Rmd: R code for the estimation of the rate of self-pollination, near-neighbour mating (proportion of seeds sired by a maternal plant from the same sampling location) and non-near-neighbour mating (proportion of seeds sired by a maternal or unsampled plant from beyond the sampling location). 

3. FPR_FNR_Error_Rates.rds: false positive (FPR) and false negative (FNR) error rates, which were specific to our parentage and sibship inference analysis. Error rates derived from the COLONY2 analysis of simulated offspring genotypes were used to correct all estimates of plant mating system parameters.