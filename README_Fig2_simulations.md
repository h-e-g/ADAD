# ADAD
### SLiM template parameter files for simulations used in Fig2.
###
### 4 sample sizes for the admixed population: 20, 100, 200 and 500 individuals
### 4 proxies of different quality (measured in FST between the proxy and the true parental population) for both parental population: 0.005, 0.01, 0.02 and 0.03 
### 6 non-stationary demographic models: 
###   -BottleneckAdmixed: 10-fold, 50 generations long bottleneck in the admixed population immediatly after the admixture event
###   -BottleneckParentalRecent: 10-fold, 50 generations long bottleneck in both parental populations immediatly after the admixture event
###   -BottleneckParentalOld: 10-fold, 50 generations long bottleneck in both parental populations immediatly after their initial split
###   -ExpgrowthAdmixed: 5% growth rate in the admixed population starting after the admixture event 
###   -ExpgrowthParentalRecent: 5% growth rate in both parental populations starting after the admixture event
###   -ExpgrowthParentalOld: 5% growth rate in both parental populations starting 500 generations before the admixture event
### 1 Default scenario (admixed population sample size = 50 individuals, no parental population proxy, constant effective population size Nadm = N1 = N2 = 10000) to be used as base comparison
###
### For each scenario, a Null Model and Adaptive Admixture templates are provided
###
### Location : folder Fig2_simulations : 
### Paths to recombination, mutation and gene content maps need to be specified, toy maps are provided in folder TOY_MAPS
### Paths to a tmp folder need to be specified (to save and restore previous simulations states)
##########################################################################################################
