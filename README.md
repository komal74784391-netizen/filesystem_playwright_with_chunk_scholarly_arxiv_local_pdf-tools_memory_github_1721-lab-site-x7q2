# Nordlys Genome Group

A small independent research group working on microbial ecology and metagenomics in Nordic environments.

## About

Nordlys Genome Group is an independent research team based in Tromsø, Norway. We combine long-read sequencing, cultivation-independent genome reconstruction and machine learning to understand how microbial communities adapt to cold, nutrient-poor habitats.

We work with universities, public-health agencies and local industry; everything we develop is released openly. Meet the team in `docs/team.md`.

## Research Themes

- Strain-resolved metagenomics of marine and soil microbiomes
- Long-read sequencing and hybrid genome assembly
- Virome discovery and host prediction
- Portable, low-cost pathogen surveillance

## Publications

### **Long-read sequencing resolves hidden microdiversity in the global ocean virome**
Hanna Ødegård‡, <mark>Anja Halvorsen</mark>‡, Mikkel Bruun, Priya Raman
*Nature Biotechnology, 2025* — [Paper](https://doi.org/10.1038/s41587-025-01917-4)
- Reports a 2.7-fold gain in strain-level recall on 918 global ocean viromes.
- Recovers 184 previously unassigned viral clusters from long-read assemblies.

### **A portable toolkit for real-time pathogen surveillance in wastewater**
Sofia Lindqvist‡, <mark>Anja Halvorsen</mark>‡, Tobias Reuter
*The Lancet Microbe, 2024* — [Paper](https://doi.org/10.1016/S2666-5247(24)00231-7)
- Detects targets within 6 hours from sampling to result.
- Achieves 0.94 AUC on 460 field wastewater samples.

### **Decoding the virome: reference-free strain resolution at scale**
<mark>Anja Halvorsen</mark>‡, Mikkel Bruun‡, Sofia Lindqvist
*Cell Host & Microbe, 2024* — [Paper](https://doi.org/10.1016/j.chom.2024.03.011)
- Graph-based assembly resolves strain haplotypes without reference genomes.
- Recovers 3.1x more novel crAssphage lineages across 1,204 metagenomes.

### **Metagenome-assembled genomes reveal a widespread nitrogen-fixing symbiosis in boreal mosses**
<mark>Anja Halvorsen</mark>, Ida Kaasa, Petter Nyström
*Nature Microbiology, 2023* — [Paper](https://doi.org/10.1038/s41564-023-01425-1)
- MAGs from 312 moss samples define a previously undescribed diazotrophic partner.
- Nitrogen fixation confirmed with 15N isotope tracing.

### **A k-mer sketching approach for rapid taxonomic profiling of low-biomass samples**
<mark>Anja Halvorsen</mark>‡, Tobias Reuter‡, Lena Petrov
*Microbiome, 2021* — [Paper](https://doi.org/10.1186/s40168-021-01160-4)
- Sketch-based classifier runs in under two minutes on a laptop.
- Maintains 0.92 F1 on mock communities down to 10^2 reads.

## Technical Capabilities

- Long-read and hybrid assembly with Flye and Medaka, polished with Pilon
- Taxonomic and functional profiling with Kraken2 and DIAMOND
- Workflow orchestration with Snakemake and Nextflow, packaged for Singularity
- Genome quality control and dereplication with CheckM2 and GTDB-Tk
- Host-prediction models trained in PyTorch

## Contact

- Email: anja.halvorsen@nordlyslab.no
- Address: Storgata 12, 9008 Tromsø, Norway
