
## Paper: Distinct colonic and cloacal microbiomes in hawksbill sea turtles (Eretmochelys imbricata) from the Northwest Indian Ocean 
 (under review)

**Code author:** Lara Kalisch  

**Manuscript authors:**  
Maximilian M.R. Polyak* and Lara Kalisch*, Matteo Monti, Francisca C. García, Chakkiath Paul Antony, Tristan Neto, Mariana Fragoso, Hasnaulhusna, Abdullah Alwali, Stephanie Köhnk, Enas Mohamed Riyaz, Isha Afeef, Claire Petros, Martin Stelfox, Raquel Peixoto  

\* These authors contributed equally.

⸻

Overview

This repository contains the analysis code used to compare colon and cloacal microbiomes in wild Eretmochelys imbricata (hawksbill sea turtles) from the Maldives.

The aim of the study is to evaluate whether cloacal samples accurately represent hindgut (colon) microbiome composition.

⸻

Repository Contents
	•	analysis.Rmd — Main analysis script containing:
	•	Data preprocessing and filtering
	•	Alpha diversity analysis
	•	Beta diversity analysis (Aitchison distance)
	•	Taxonomic composition
	•	Differential abundance testing (ANCOM-BC2)

⸻

How to Run

Open analysis.Rmd in RStudio and knit the document to reproduce all analyses and figures.

⸻

Requirements
	•	R (>= 4.3.0)
	•	Recommended: RStudio
	•	Required packages: phyloseq, vegan, microbiome, ANCOMBC, ggplot2, etc.

⸻

Data Availability

Raw sequencing data are available in the European Nucleotide Archive (ENA) under accession number: PRJEB111895

