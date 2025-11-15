# Computational Biology and Cancer Epigenetics
> **Mission:** We develop data-driven methods to decode how chromatin state, DNA methylation, and transcriptional programs shape tumor behavior — and we turn these insights into robust diagnostics and decision-support tools.

## Overview
Our lab combines single‑cell and single‑molecule assays with statistical learning to study cancer epigenetics and therapy response. We routinely integrate scCUT&Tag/ChIC (e.g., H3K4me1, H3K9me2/3), scRNA‑seq, scATAC‑seq, CyTOF‑based epigenetic cytometry, and liquid‑biopsy readouts (EPINUC-like plasma nucleosome profiling), building harmonized analysis pipelines across modalities. Inspired by, and in close collaboration with, the [Shema Lab](https://www.weizmann.ac.il/dept/irb/shema/) at the Weizmann Institue of Science, particularly on single‑cell epigenetic analysis of tumors, multi‑parametric plasma nucleosome assays, and disease‑focused epigenetic rewiring, we emphasize rigorous, quantitative integration that can translate to the clinic. 

## Focus Areas

### 1) Single‑cell epigenetic heterogeneity in solid and hematologic tumors 
<img style="float: right; clear:right;" src="/images/Bio/SingleCell.png" alt="The MUSE Platform" width="400"/>
We model tumor cell‑state diversity directly from histone‑mark and chromatin‑regulator profiles, and connect these states to proliferation, stemness, lineage, and drug sensitivity. Our approach draws on epigenetic‑CyTOF profiling of tumors to resolve subpopulations and their therapeutic vulnerabilities, which aligns with research threads on single‑cell epigenetic analysis of tumors. 

### 2) Liquid biopsy epigenetics (plasma‑isolated nucleosomes, DNA methylation, and proteins) 
<img style="float: right; clear:right;" src="/images/Bio/EPINUC.png" alt="The MUSE Platform" width="400"/>
We develop multi‑layer pipelines that infer tissue‑of‑origin and tumor activity from circulating nucleosomes and biomarkers, combining nucleosome‑localized histone marks, DNA methylation, fragmentomics, and protein biomarkers at the single‑molecule level. These pipelines are designed to work from minimal input and support serial patient monitoring.

### 3) Disease programs and epigenetic rewiring
We build disease‑specific models of epigenetic reprogramming, focusing on:
- **B‑cell lymphomas:** EZH2 gain‑of‑function vs. KMT2D loss‑of‑function and their combinatorial effects on the epigenetic network; quantification of heterogeneity and cross‑talk. 
- **IDH‑mutant gliomas:** coupling between metabolism and chromatin; rapid loss of histone acetylation and increased heterogeneity in mutant‑IDH contexts. 
- **Breast cancer plasticity:** enhancer and repression landscapes underlying luminal/basal states; microenvironmental interactions; therapy‑response phenotypes. 
- **Pancreatic cancer:** epigenetic states of cancer, immune, and CAF compartments; therapy‑induced adaptations; potential for non‑invasive monitoring via plasma nucleosome signatures. 
- **Stem‑cell networks:** systems‑level effects of H3K27 perturbations on the broader epigenetic network during early differentiation. 

## Methods & Tooling

- **Multi‑omic integration**
- **Signal modeling** 
- **Heterogeneity metrics:** entropy/dispersion measures, Vendi‑style diversity, pathway‑level UCell scoring, and set‑based explanations (SHAP‑like) for interpretable state calls.
- **Liquid‑biopsy analytics:** single‑molecule event parsing; joint modeling of histone PTMs, methylation, and protein tags per fragment; robust tissue‑contribution estimates.

