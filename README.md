# Soil-microbiome-after-Mnt-BC-application
This script analyzes microbial community dynamics in thallium-contaminated soil treated with  montmorillonite-biochar (Mnt-BC) composite over a 60-day cultivation period.
The analysis examines:
1. Alpha and beta diversity changes over time
2. Community structure shifts using PCoA
3. Taxonomic composition at phylum level
4. Network properties and their temporal dynamics
5. Community cohesion and resilience patterns in relation to pH

IMPORTANT: Before running this script, ensure that your working directory contains 
the 'data.xlsx' file with the following worksheets:
- "metadata": Sample metadata including Day and pH values
- "ASVs": ASV abundance table
- "Taxonomy": Taxonomic classifications for ASVs

Example: 
setwd("/path/to/directory/containing/data.xlsx")
