# ML-Based Intrusion Detection in SDN (Software Defined Network)

This repository contains implementations of two machine learning (ML)-based approaches for Intrusion Detection in Software Defined Networks (SDN). The methods are based on two research papers and have been implemented to identify and mitigate security threats within SDN environments.

## Table of Contents
- [Overview](#overview)
- [Approaches](#approaches)
  - [Approach 1: Research Paper 1](#approach-1-research-paper-1)
  - [Approach 2: Research Paper 2](#approach-2-research-paper-2)
- [Dataset](#dataset)
- [Presentation](#presentation)
- [Installation](#installation)


## Overview

Software Defined Networking (SDN) has emerged as a revolutionary paradigm in networking, enabling dynamic management and control of network behavior via software. However, it has also introduced new vulnerabilities that are susceptible to various types of network attacks. This project explores the use of machine learning techniques to enhance the security of SDN by detecting potential intrusions.

Two different research approaches are explored for ML-based intrusion detection in SDN:
1. **Approach 1:** A method based on the research paper: ["An Intrusion Detection System for SDN Using Machine Learning"](https://www.techscience.com/iasc/v35n1/48147).
2. **Approach 2:** A method inspired by the paper: ["Machine learning-based network intrusion detection for big and imbalanced data using oversampling, stacking feature embedding and feature extraction"](https://journalofbigdata.springeropen.com/articles/10.1186/s40537-024-00886-w).

## Approaches

### Approach 1: Research Paper 1
The first approach implements the method proposed in the paper. This approach focuses on **binary classification** for detecting malicious activities within an SDN environment, using the **NSL-KDD** dataset, an enhanced version of the KDD 1999 dataset.

- **Binary Classification:** A Decision Tree classifier was used, achieving an accuracy of **87%** for detecting normal vs. attack traffic.

- **Key Features**:
  - Uses flow-based features for classification.
  - Employs a simple yet effective Decision Tree classifier....
  - Targets a binary classification task (normal vs. attack ).

### Approach 2: Research Paper 2
The second approach is inspired by . This method focuses on **multiclass classification** using advanced machine learning models such as Extra Trees, applied to the same **NSL-KDD** dataset.

- **Multiclass Classification:** An Extra Trees classifier was employed, achieving an accuracy of **99.8%** in distinguishing between various types of attacks (e.g., DoS, Probe, U2R, R2L).

- **Key Features**:
  - Focuses on multiclass classification to detect various types of network attacks.
  - Uses advanced machine learning models like Extra Trees....
  - Incorporates both the detection of different attack categories (DoS, Probe, U2R, R2L) and normal traffic.

## Dataset

Both approaches are trained and evaluated using the **NSL-KDD dataset**, an enhanced version of the original KDD 1999 Cup dataset. The NSL-KDD dataset addresses some inherent issues in the original KDD data, such as duplicate records, and provides a more reliable benchmark for evaluating intrusion detection systems.

- **Dataset Link**: [NSL-KDD Dataset](https://www.unb.ca/cic/datasets/nsl.html)

## Presentation

A presentation summarizing the project, its approaches, and key results is available in this repository. You can find the presentation [here](./presentation.pdf).
## Research Paper 

 You can find the paper [here](./Research_Paper.pdf).

## Installation

To set up the project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/MeryemBenSalem/ML-Based-Intrusion-Detection-for-SDN-Based-Broadband-Networks.git
   
