# MDGE 610: kallisto EM Assignment

Assignment materials for Session 5 of MDGE 610: Foundations of Bioinformatics.

## Overview

In this assignment, students investigate the Expectation-Maximization (EM) algorithm as implemented in kallisto, a tool for RNA-seq transcript quantification. Students will examine convergence criteria and empirically test their effect on estimation accuracy.

## Contents

| File | Description |
|------|-------------|
| `assignment_handout.pdf` | Assignment instructions |
| `assignment_handout.tex` | LaTeX source for the handout |
| `1977 DLR EM paper.pdf` | Required reading: Dempster, Laird & Rubin (1977) |
| `gencode.v44.kidx` | Pre-built kallisto index (GENCODE v44 protein-coding transcripts) |
| `sim_reads_1.fastq.gz` | Simulated paired-end reads (read 1) |
| `sim_reads_2.fastq.gz` | Simulated paired-end reads (read 2) |
| `sim_true_counts.txt` | Ground truth transcript counts |

## Simulated Data

- **Reference**: GENCODE v44 human protein-coding transcriptome (110,962 transcripts)
- **Read pairs**: 1,000,000
- **Read length**: 75 bp paired-end
- **Fragment length**: Mean 250 bp, SD 50 bp
- **Sequencing error**: 1% per-base

## Usage

Students should download these materials and follow the instructions in `assignment_handout.pdf`. The assignment requires obtaining and modifying the kallisto source code from https://github.com/pachterlab/kallisto.
