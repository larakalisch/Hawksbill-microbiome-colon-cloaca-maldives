
#Colon vs Cloaca Microbiome in Hawksbill Sea Turtles

Authors: Maximilian M.R. Polyak1, 2, 3, 6+, Lara Kalisch2+, Matteo Monti2, Francisca C. García2, Chakkiath Paul Antony2, Tristan Neto3, Mariana Fragoso3, 6, Hasnaulhusna3, Abdullah Alwali1 , Stephanie Köhnk3, Enas Mohamed Riyaz5, Isha Afeef4, Claire Petros6, Martin Stelfox3, Raquel Peixoto2

Paper: Distinct colonic and cloacal microbiomes in hawksbill sea turtles (Eretmochelys imbricata) from the Northwest Indian Ocean 
 (under review)

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

