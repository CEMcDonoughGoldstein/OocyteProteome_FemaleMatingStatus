# OocyteProteome_FemaleMatingStatus
Analysis of proteome data for research "Female mating status influences protein composition of mature Drosophila oocytes."
Manuscript in revision at Scientific Reports

In this project we investigated how female mating status influenced the proteome composition of mature (stage 14) oocytes.
Ooyctes were collected from either unmated females or females mated 24 hrs after mating (with oocytes accumulating from 12 to 24 hrs after mating and having matured in a mated female environment; see experimental_design.pdf figure). Females were mated to isotopically labeled males so no male proteins are detected in this analysis.
6-plex (3 replicates per condition) TMT quantitative proteomics on a Lumos Orbitrap mass spectrometer and data was processed with Proteome Discoverer v 2.3 and Mascot v 2.6 all subsequent anlayses were conducted with R
We robustly identified 4,485 oocyte proteins and revealed that stage-14 oocytes from mated females differed significantly in protein composition relative to oocytes from unmated females, with 296 proteins more abundant in oocytes from mated females and 200 more abundant in oocytes from unmated females.
Differentially abundant proteins in mated females formed a highly interconnected network enriched for translational machinery and transmembrane proteins were increased in oocytes , including calcium binding and transport proteins.

Raw data is available at ProteomeXchange PXD022142

We compared mating influences on the oocyte proteome with eisting data on decrease in translational efficiency (Greenblatt et al. 2019) changes in oocyte proteome during maturation (stage 11 to stage 14; Kronja et al. 2014a), activation (Kronja et al. 2014b), and changes during activation of phosphorylated proteins (Zhang et al. 2019). All files involved in comparing to published data can be found in the folder /ComparisonsPublishedData 

This repository includes all data and code necessary to replicate the analyses reproted in the manuscript.
The code is found in "Analysis_code.rmd" and the oocyte proteome data is "P473_100619_Proteins.txt" all other files are for comparisons to other datasets.
For any qestions contact Caitlin at mcdonouce@gmail.com
