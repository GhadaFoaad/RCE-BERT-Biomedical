DATASET FILES FOR REPRODUCIBILITY
=====================================

This repository contains the code and resources for the paper: **"A Knowledge Recall Framework for Biomedical Abbreviation Disambiguation Using Pre-trained Transformer Models"**, submitted to IEEE Access.

## Overview
This project introduces **Recalled Concept Embedding (RCE)**, a novel method to query latent knowledge from pre-trained transformers (like SciBERT) for disambiguating biomedical abbreviations.

## Requirements
*   Python 3.8+
*   PyTorch
*   Hugging Face Transformers

Install dependencies:
```bash
pip install -r requirements.txt
  
Dataset
This code is compatible with:
•	MeDAL Subset: (https://www.kaggle.com/datasets/xhlulu/medal-emnlp)
•	MSH WSD: (https://huggingface.co/datasets/bigbio/msh_wsd)
How to Run
1.	Place your dataset CSV in the root folder.
2.	Run the training script:
