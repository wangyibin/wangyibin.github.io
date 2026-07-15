---
title: "C-Phasing"
summary: "A chromosome-scale assembly framework for haplotype-resolved reconstruction of polyploid genomes using Hi-C and Pore-C data."
tags:
  - Computational Genomics
  - Polyploid Genome Assembly
  - Pore-C
  - Hi-C
  - Rust
links:
  - name: GitHub
    type: github
    icon: github
    url: "https://github.com/wangyibin/CPhasing"
  - name: Nature paper
    url: "/publications/wang-genetic-architecture-sugarcane-2026/"
  - name: Bioinformatics paper
    url: "/publications/wang-mike-ultrafast-assembly-2024/"
---

## Overview
C-Phasing is an open-source framework for chromosome-scale, haplotype-resolved assembly of polyploid genomes. It integrates long-read sequencing, Hi-C and Pore-C chromatin interaction data to accurately reconstruct homologous chromosomes in complex genomes with high ploidy and low sequence divergence.

Designed for modern polyploid genome projects, C-Phasing provides an end-to-end solution from chromosome partitioning to scaffolding while remaining compatible with both conventional Hi-C and long-read Pore-C technologies.

## Key Features

- Hypergraph-based chromosome partitioning using multi-way chromatin interactions
- Support for both Hi-C and Pore-C data
- Methylation-assisted alignment refinement (MethAlign)
- Chimeric contig detection (Hitig)
- Copy-number-aware collapsed contig rescue (CollapseRescue)
- Chromosome-scale scaffolding for complex polyploid genomes

## Applications

C-Phasing has been evaluated across a diverse collection of polyploid genomes, including potato, sweet potato, alfalfa, sugarcane and other complex plant genomes, consistently improving chromosome completeness, haplotype resolution and structural accuracy.

## Resources

- Source code: https://github.com/wangyibin/CPhasing
- Documentation: *https://wangyibin.github.io/CPhasing*
- Latest Nature paper: [Genetic Architecture of Sugarcane Traits in a Polyploid Genomics Framework](/publications/wang-genetic-architecture-sugarcane-2026/)
- Bioinformatics paper: [MIKE: An Ultrafast, Assembly-, and Alignment-Free Approach for Phylogenetic Tree Construction](/publications/wang-mike-ultrafast-assembly-2024/)
