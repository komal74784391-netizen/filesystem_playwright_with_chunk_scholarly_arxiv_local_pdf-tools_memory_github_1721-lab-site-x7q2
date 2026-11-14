# Project Spotlight — portable wastewater surveillance

Status: active · Lead: Anja Halvorsen

## What we do

Spotlight turns municipal wastewater samples into same-day pathogen signals
for regional health agencies. Samples are sequenced on portable long-read
devices and processed on site.

## Methods and software in use

- Oxford Nanopore long reads assembled with Flye; consensus polished with Medaka.
- Read-level classification with Kraken2 against a curated viral database.
- Assembly correction with Pilon for low-coverage amplicon runs.
- Pipelines orchestrated with Snakemake and shipped in Singularity containers.
