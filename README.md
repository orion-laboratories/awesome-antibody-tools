# Awesome Antibody Tools
List of databases and tools to discover, develop, and engineer antibodies.
The goal is to create a comprhensive list of tools and databases for antibody-related predictions. With this effort we are also aiming to create a gold standard for benchmarking antibody-antigen predictions.

## Datasets
This repository contains a manually curated dataset of protein-antigen pairs that are not likely to be used for training of the methods mentioned below

- https://adcdb.idrblab.net/

- [Antibody Registry](https://antibodyregistry.org/)  

- [Observed Antibody Space (OAS)](http://opig.stats.ox.ac.uk/webapps/oas/)

- https://opig.stats.ox.ac.uk/webapps/plabdab, github: https://github.com/brennanaba/PLAbDab

- http://research.naturalantibody.com/paddocumentation


## Tools

### AI-based antibody-antigen prediction
- AbAgIntPre: - http://www.zzdlab.com/AbAgIntPre/ https://www.frontiersin.org/journals/immunology/articles/10.3389/fimmu.2022.1053617/full https://github.com/emersON106/AbAgIntPre
  
- ImaPEp: - https://www.mdpi.com/1422-0067/25/10/5434 https://github.com/3BioCompBio/ImaPEp

- GeoFlow: not open-source but available for non-commercial applications

- Geometric Paratope Epitope Prediction: https://github.com/Marco-Peg/GEP

- Antipasti: binding affinity prediction https://github.com/kevinmicha/ANTIPASTI

- **[AbSciBio/unlocking-de-novo-antibody-design](https://github.com/AbSciBio/unlocking-de-novo-antibody-design)**  
  *Generative AI for de novo design of antibody sequences.*  
  Repository includes datasets and design outputs for novel antibody candidates.

- **[AIforGreatGood/biotransfer](https://github.com/AIforGreatGood/biotransfer)**  
  *Machine learning–driven framework for designing high-affinity scFv libraries.*  
  Uses Bayesian language models for in silico candidate optimization.

- **[luost26/diffab](https://github.com/luost26/diffab)**  
  *Diffusion-based generative model for antigen-specific antibody design and optimization.*  
  Developed and presented at NeurIPS 2022.
  Benchmark: https://github.com/AstraZeneca/DiffAbXL

- **[pengzhangzhi/ab_opt](https://github.com/pengzhangzhi/ab_opt)**  
  *Generative Diffusion Models for Antibody Design, Docking, and Optimization.*  
  Provides an end-to-end pipeline that integrates design with docking and experimental validation data.

- **[IgGM (TencentAI4S/IgGM)](https://github.com/TencentAI4S/IgGM)**  
  *A generative model for functional antibody and nanobody design.*  
  Can design overall structures as well as specific CDR loops based on antigen and epitope inputs.

- **[LizeRaes/ai-drug-discovery](https://github.com/LizeRaes/ai-drug-discovery)**  
  *A demo application using LangChain4j for AI-backed drug discovery research.*  
  Includes steps to derive new candidate antibodies from antigen sequence and known antibody features.

- GeoAB: https://github.com/EDAPINENUT/GeoAB


### Docking-based antibody-antigen prediction
- GeoFlow - not open-source but available for non-commercial applications

- AbAdapt - predict most likely pose from AA sequences of antigen + antibody https://sysimm.org/abadapt/workflow

### General PPI prediction tools that can be applied here

- Boltz2 https://github.com/jwohlwend/boltz?tab=readme-ov-file

- DiffDockPP - AI-driven MD for PPI

- AlphaFold

- HADDOCK



### Antibody optimization tools
#### improve affinity
- AttABseq
"Unsupervised evolution of protein and antibody complexes with a structure-informed language model". https://github.com/varun-shanker/structural-evolution https://www.science.org/stoken/author-tokens/ST-1968/full

- **[oxpig/AntiFold](https://github.com/oxpig/AntiFold)**  
  *Antibody-specific inverse folding model for structure-based design.*  
  Fine-tuned from ESM-IF1 to predict sequences that fold into a desired antibody structure with optimized binding properties.

- MEAN: https://github.com/THUNLP-MT/MEAN


#### improve developelability

- **[gv20-therapeutics/antibody-in-pytorch](https://github.com/gv20-therapeutics/antibody-in-pytorch)**  
  *PyTorch implementations of machine learning models for antibody sequence analysis.*  
  Includes models for affinity, developability, and general sequence evaluation.

- **[Mohammad-Vahed/AI-BioDiscover](https://github.com/Mohammad-Vahed/AI-BioDiscover)**  
  *An AI/ML tool for antibody design and molecular property prediction.*  
  A demo app that walks through candidate discovery and property evaluation.

#### humanization


### Other Antibody Tools
EvolvePro - https://github.com/mat10d/EvolvePro https://www.science.org/doi/10.1126/science.adr6006 https://github.com/idmjky/EvolvePro
It requires experimental measure for optimization and training

#### Antibodies language
- AbLEF antibody language https://github.com/Merck/AbLEF https://academic.oup.com/bioinformatics/article/40/5/btae268/7646845

- **[Graylab/IgLM](https://github.com/Graylab/IgLM)**  
  *Generative language model for antibody design.*  
  Supports sequence infilling, full sequence generation, and sequence evaluation (e.g. redesigning CDR loops).

- **[oxpig/AbLang2](https://github.com/oxpig/AbLang2)**  
  *An antibody-specific language model for predicting non‑germline (mutated) residues.*  
  Useful for guiding antibody humanization and optimization.

#### Structure prediction tools

- **[Graylab/IgFold](https://github.com/Graylab/IgFold)**  
  *State-of-the-art antibody structure prediction from sequence alone.*  
  Leverages pretrained language models (e.g. AntiBERTy) to rapidly predict antibody 3D structures.

- **[RoseTTAFold](https://github.com/RosettaCommons/RoseTTAFold)**  
  *Deep learning-based protein (and antibody) structure prediction tool.*  
  Although not antibody‑specific, it is widely used in antibody modeling and design.

- **Rosetta@home & RosettaCommons Tools**  
  *A suite of computational tools for protein structure prediction, docking, and design.*  
  Accessible via public servers and repositories; note that many parts of Rosetta are licensed for academic use.

- **[HADDOCK-antibody-antigen](https://github.com/haddocking/HADDOCK-antibody-antigen)**  
  *Protocol for antibody–antigen docking using HADDOCK.*  
  Supports modeling of antibody–antigen complexes.


## AB funnel pipeline

antigen -> antigen structure + seq -> predicted AB or starting AB -> AB structure prediction  -> improve affinity -> improve developelability -> docking



## Contribute
To contribute open a new issue with your suggestions.

