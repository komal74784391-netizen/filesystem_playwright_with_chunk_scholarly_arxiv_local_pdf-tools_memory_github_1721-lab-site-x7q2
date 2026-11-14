# Project DeepIso — marine virome microdiversity

Status: active · Lead: Sofia Lindqvist

## What we do

DeepIso profiles microdiversity in ocean viromes from depth-resolved
sampling transects in the North Atlantic.

## Methods and software in use

- metaFlye assemblies from deep-sequencing transects.
- Genome completeness and contamination screening with CheckM2; taxonomy with GTDB-Tk.
- Protein-level similarity search with DIAMOND.
- Host-prediction neural networks trained in PyTorch on GPU nodes.
- Nextflow DSL2 pipelines for reproducible re-processing.
