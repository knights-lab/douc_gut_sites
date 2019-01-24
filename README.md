# douc_gut_sites
Microbiome of red-shanked douc gut sites : analysis

### Required R Packages
* vegan, ape, phyloseq, ggplot2, ggsignif, gplots, RColorBrewer, robCompositions, polycor, beeswarm, reshape2, ltm
<br><br>

### Data Files
The OTU (Operational Taxonomic Unit) and taxa tables used in analysis were generated using closed-reference OTU picking in the taxonomy-aware exhaustive optimal alignment program [BURST](https://github.com/knights-lab/BURST) against the GreenGenes (version 13_8) database, clustered at 97% identity, with an alignment rate of 93.9 percent.
#### Files:
* douc_stomach_vs_feces_matching_mapfile_082417.txt - metadata
* douc_stomach_vs_feces_taxatable_gg97.txt - taxa table
* douc_stomach_vs_feces_otutable_gg97.txt - OTU table
* gg97.tre - GreenGenes tree file
* douc_dtomach_vs_feces_otutable_gg97_predictions_categorized_L3.txt - PICRUSt table
<br><br>

### Running the Analysis

To complete the Douc Gut Site analysis, for all work presented in the manuscript, you can run through the R script provided in the bin, douc_stomach_vs_feces_gg97.R. This script walks through all statistical tests mentioned in the manuscript, and generates all the figures used.

This script is designed to be run from within the bin directory.
