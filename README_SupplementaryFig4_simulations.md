# ADAD
### SLiM template parameter files for simulations used in Fig3 + file with all explored parameter values.
### A Null Model and Adaptive Admixture templates are provided
### Explored parameter values are in the file "Fig3_simparams.txt"
###   each row is a possible combination of explored parameters: Tdiv, N1, N2, Nadm, s, Fonset, alpha and Tadm (see Methods and Supplementary Table 1)
###   values for Tonset (associated to Fonset, the theoretical frequency, at the time of admixture, of the beneficial mutation) were determined using previous results described in Stephan et al. 1992
###   because of high variance in the empirical Fonset values, simulations were regrouped based on these empirical values instead on the theoretical to study the effect of Fonset on detection power (see Supplementary Fig6)
###   there are 32956 parameter combinations in total 
###
### Placeholders for parameter values need to be replaced in both templates by the values in "Fig3_simparams.txt", all placeholders replaced by parameter values in the same row
###   ex. TONSET1 replaced by 4145 (taken from column TONSET1) , TSPLIT1 replaced by 4101 (taken from column TSPLIT1) and so on
### The values are already rescaled
###
### Location : folder Fig3_simulations : 
### Paths to recombination, mutation and gene content maps need to be specified, toy maps are provided in folder TOY_MAPS
### Paths to a tmp folder need to be specified (to save and restore previous simulations states)
##########################################################################################################
