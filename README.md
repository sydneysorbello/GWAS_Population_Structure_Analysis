# GWAS_Population_Structure_Analysis
**This code was produced as part of an assignment for a graduate course in bioinformatics.** 

Description of Data:
This code investigates 5 populations and the subsequent population structure found during GWAS analysis.
The provided data included individuals from the Framingham Heart Study. This group makes up two populations, cases and controls. 
This dataset featured predominantly americans of european descent.
As this analysis will illustrated, a few individuals were more similar to those of non-european descent.
The other 3 populations were derived from HapMap data collected for European (CEU) and Yoruba (YRI) populations as well as a combination of individuals from Beijing, China and Tokyo, Japan (CHB+JPT).

We will start by pruning a merged dataset containing all populations, 'all_pops'. Once, we have the pruned dataset 'all_pops_pruned' we can then perform PCA to compare populations structure. 
