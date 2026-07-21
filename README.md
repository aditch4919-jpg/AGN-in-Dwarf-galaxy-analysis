# AGN-in-Dwarf-galaxy-analysis
An independent data analysis project examining whether broad-line AGN in local dwarf galaxies are consistent with the published black hole–stellar mass (M_BH–M★) scaling relation for active galaxies.

# Key Result
The broad-line dwarf AGN subsample from Reines, Greene & Geha (2013) sits broadly consistent with the Reines & Volonteri (2015) M_BH–M★ relation, with a median offset of −0.09 dex — indicating no significant systematic departure from the general AGN population at the low-mass end.

One notable outlier: RGG 118 sits −1.10 dex below the relation, consistent with its known status as hosting one of the smallest confirmed black holes in any galaxy nucleus (~50,000 M☉; Baldassare et al. 2015).

# Data Sources
Catalog: Reines, Greene & Geha (2013), ApJ 775, 116
136 dwarf galaxies (z < 0.06) with optical signatures of AGN activity from SDSS-DR8
Retrieved from VizieR: J/ApJ/775/116/bhgal
Direct link: https://vizier.cds.unistra.fr/viz-bin/VizieR?-source=J/ApJ/775/116

To reproduce the analysis, download the catalog from VizieR in semicolon-separated format (;-Separated-Values) and save as asu.tsv in the project root.

Black hole masses: Reines & Volonteri (2015), ApJ 813, 82
M_BH estimates for 12 broad-line dwarf AGN (their Table 3)
Hardcoded directly in the notebook from the published table
Paper: https://arxiv.org/abs/1508.06274
Comparison relation: Reines & Volonteri (2015)

log(M_BH/M☉) = α + β × (log M★/M☉ − 11)
α = 7.45 ± 0.08, β = 1.05 ± 0.11

# References
Reines, A. E., Greene, J. E., & Geha, M. (2013), ApJ 775, 116 — ADS
Reines, A. E. & Volonteri, M. (2015), ApJ 813, 82 — ADS
Baldassare, V. F. et al. (2015), ApJ 809, L14 — discovery of RGG 118's ~50,000 M☉ black hole

# Author
Aditi Chaudhary
3rd Year Undergraduate, Engineering Physics
Delhi Technological University, India
aditch4919@gmail.com | LinkedIn | GitHub
