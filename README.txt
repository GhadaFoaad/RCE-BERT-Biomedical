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
•	MeDAL dataset: (https://www.kaggle.com/datasets/xhlulu/medal-emnlp)
•	MSH WSD: (https://huggingface.co/datasets/bigbio/msh_wsd)
How to Run
1.	Place your dataset CSV in the root folder.
2. For the MeDaL dataset, run script: MeDAL_Script.ipynb to create subset
3.  Run the Preprocessing script : Preprocessing.ipynb
4.	Run the training script: train_model(RCE_FULL_Model).ipynb
5.	The script will train the model (using your specified transformer) using 3 random seeds and output the Mean/STD results.
