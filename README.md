[![GitHub release (latest by date)](https://img.shields.io/github/v/release/nextstrain/ncov)](https://github.com/nextstrain/ncov/releases)
[![See recent changes](https://img.shields.io/badge/changelog-See%20recent%20changes-blue)](https://docs.nextstrain.org/projects/ncov/en/latest/reference/change_log.html)

WIP Nextstrain template

# About

This repository is a copy of [Nextstrain](https://nextstrain.org) to understand how SARS-CoV-2, the virus that is responsible for the COVID-19 pandemic, evolves and spreads.

# Quick install 

[Install Nextstrain](https://docs.nextstrain.org/en/latest/install.html)

```
git clone https://github.com/concentricbyginkgo/ncov

nextstrain view ncov/auspice
```

Open in browser

More information on [viewing](https://docs.nextstrain.org/en/latest/tutorials/running-a-workflow.html)

## Bioinformatics notes

Site numbering and genome structure uses [Wuhan-Hu-1/2019](https://www.ncbi.nlm.nih.gov/nuccore/MN908947) as reference. The phylogeny is rooted relative to early samples from Wuhan. Temporal resolution assumes a nucleotide substitution rate of [8 &times; 10^-4 subs per site per year](http://virological.org/t/phylodynamic-analysis-176-genomes-6-mar-2020/356). There were SNPs present in the nCoV samples in the first and last few bases of the alignment that were masked as likely sequencing artifacts.


