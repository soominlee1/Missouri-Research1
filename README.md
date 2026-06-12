# UCIe-SI-Lab

Open-source tools for UCIe channel analysis, signal integrity evaluation, and HFSS workflow automation.

## Overview

UCIe-SI-Lab is an open-source research toolkit developed for high-speed interconnect and advanced packaging studies. The project focuses on automating simulation workflows, analyzing S-parameters, evaluating mode conversion, and investigating signal integrity issues in UCIe-based chiplet systems.

The toolkit was developed during undergraduate research activities involving advanced semiconductor packaging, differential signaling, via transition analysis, microbump characterization, and channel optimization.

## Features

* HFSS simulation workflow automation
* S-parameter parsing and processing
* Differential-to-common mode conversion analysis
* Insertion loss and return loss extraction
* Eye diagram post-processing
* Via stub impact evaluation
* Surface roughness sensitivity analysis
* Microbump channel characterization
* Batch design-of-experiments (DOE) processing
* Automated report generation

## Research Topics

This repository contains scripts and utilities related to:

* UCIe channel design
* Signal Integrity (SI)
* Power Integrity (PI)
* Differential interconnects
* Via transitions and stubs
* Surface roughness effects
* Advanced packaging
* Glass and organic interposers
* Chiplet communication systems

## Repository Structure

```text
UCIe-SI-Lab/
├── scripts/
│   ├── hfss_automation/
│   ├── sparameter_analysis/
│   ├── eye_processing/
│   └── mode_conversion/
├── examples/
├── datasets/
├── reports/
└── docs/
```

## Example Applications

* Automated extraction of SDD21, SCD21, SCC21, and SDC21
* Via stub mode conversion studies
* Surface roughness impact analysis
* UCIe channel performance evaluation
* Microbump signal integrity assessment
* High-speed package optimization

## Goals

The goal of this project is to improve reproducibility and productivity in signal integrity research by providing open-source tools that reduce repetitive simulation and data-processing tasks.

Researchers, students, and engineers are welcome to use, modify, and contribute to the project.

## License

MIT License
