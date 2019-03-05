# VA-ECLS Survival Analysis with scRNASeq

Technical description of analysis of scRNASeq data for our forthcoming VA-ECLS survival paper. See final_analysis.rmd (or its knitted version, final_analysis.html) for details.

# GEO Submission Status

The raw counts matrix is available from GEO under accession [GSE127221](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE127221)

The processed data file `PBMC_merged_filtered_recoded.rds` will need to be downloaded from GEO to complete the analysis described here.  Note that `PBMC_merged_filtered_recoded.tab` (the tab delimited version of the datafile) will also be available from GEO, but if you are using R the .rds file is much smaller and easier to work with (but requires that you have the Matrix package installed.) The subject metadata needed to complete the analysis (metadata.rds) also is required--it will be available from GEO, but for convenience it is also a part of this repo (in the Final_Data directory).
