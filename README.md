# Awesome Antibody Tools
List of databases and tools to discover, develop, and engineer antibodies.
The goal is to create a comprhensive list of tools and databases for antibody-related predictions. With this effort we are also aiming to create a gold standard for benchmarking antibody-antigen predictions.

## Datasets
This repository contains a manually curated dataset of protein-antigen pairs that are not likely to be used for training of the methods mentioned below

https://adcdb.idrblab.net/

## Tools

### AI-based antibody-antigen prediction
AbAgIntPre: - http://www.zzdlab.com/AbAgIntPre/ https://www.frontiersin.org/journals/immunology/articles/10.3389/fimmu.2022.1053617/full https://github.com/emersON106/AbAgIntPre

ImaPEp: - https://www.mdpi.com/1422-0067/25/10/5434 https://github.com/3BioCompBio/ImaPEp

GeoFlow: not open-source but available for non-commercial applications

Geometric Paratope Epitope Prediction: https://github.com/Marco-Peg/GEP

### Docking-based antibody-antigen prediction
GeoFlow - not open-source but available for non-commercial applications
AbAdapt - predict most likely pose from AA sequences of antigen + antibody https://sysimm.org/abadapt/workflow

### General PPI prediction tools that can be applied here

DiffDockPP - AI-driven MD for PPI

AlphaFold

HADDOCK



### Antibody optimization tools
#### improve affinity
AttABseq

"Unsupervised evolution of protein and antibody complexes with a structure-informed language model". https://github.com/varun-shanker/structural-evolution https://www.science.org/stoken/author-tokens/ST-1968/full

#### improve developelability

#### humanization


### Other Antibody Tools
EvolvePro - https://github.com/mat10d/EvolvePro https://www.science.org/doi/10.1126/science.adr6006 https://github.com/idmjky/EvolvePro
It requires experimental measure for optimization and training

AbLEF antibody language https://github.com/Merck/AbLEF https://academic.oup.com/bioinformatics/article/40/5/btae268/7646845


## Leaderboard

All methods should be added to a docker and tested on a gold-standard database.

|Method|Description|AUC|
|------|-----------|---|
|TBD|TBD|0.5|


## Contribute


