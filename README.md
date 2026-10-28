# SLAM-seq | Nascent RNA Analysis

**A computational workflow for investigating nascent transcription and RNA dynamics using SLAM-seq data.**

## 🧬 Overview

SLAM-seq (Thiol-linked Alkylation for the Metabolic Sequencing of RNA) is a metabolic RNA-labeling approach that enables the identification and quantification of newly synthesized RNA.

By incorporating 4-thiouridine (4sU) into newly transcribed RNA, followed by chemical alkylation and RNA sequencing, SLAM-seq allows newly synthesized RNA to be distinguished from pre-existing RNA through characteristic T-to-C nucleotide conversions.

This repository is intended to document computational approaches for processing SLAM-seq data, assessing nucleotide conversion rates, investigating changes in nascent transcription, and visualizing transcriptional responses across experimental conditions.

The workflow is particularly relevant to studying transcriptional regulation and RNA dynamics in cancer biology.

## 🎯 Objectives

The main objectives of this analysis are to:

- Process and perform quality control of SLAM-seq sequencing data.
- Identify T-to-C nucleotide conversions associated with newly synthesized RNA.
- Quantify nascent RNA abundance across experimental conditions.
- Investigate changes in transcriptional activity following experimental perturbations.
- Identify genes exhibiting significant changes in newly synthesized RNA.
- Visualize global and gene-specific transcriptional responses.
- Facilitate integration of SLAM-seq results with conventional RNA-seq and other omics datasets.

## 🔬 Analysis workflow

```text
Raw sequencing data (FASTQ)
            |
            v
Sequence quality control
            |
            v
Read preprocessing
            |
            v
Read alignment and SLAM-seq processing
            |
            v
T-to-C conversion detection
            |
            v
Conversion rate and sample QC
            |
            v
Nascent RNA quantification
            |
            v
Statistical analysis
            |
            v
Differential transcription analysis
            |
            v
Data visualization
            |
            v
Biological interpretation
