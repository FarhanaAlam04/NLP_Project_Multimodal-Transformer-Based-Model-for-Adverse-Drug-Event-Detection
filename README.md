# NLP_Project_Multimodal-Transformer-Based-Model-for-Adverse-Drug-Event-Detection

## Project Overview
This project aims to detect Adverse Drug Events (ADEs) from drug-effect pairs and later along with structured data also using a transformer-based approach. We use two different strategies:
- **Part 1**: Multi-label ADE prediction
- **Part 2**: Single-label Effect Category classification
- **Part 3**: Multimodal ADE detection 
## Datasets Used
- ADE-Corpus-V2
- CADEC v2 (SCT)
- FAERS structured dataset
## Files
‘NLP_Project_Dataset-Final Cleaning_25CategoryCreation.ipynb’ – ADE+CADEC Dataset  preprocessing, and label Creation
‘ADEandCADEC-FinalJoining-Modeling-2.ipynb’ –  predict ADEs from “Drug + Effect”
‘ADEandCADDEC-withCategory.ipynb’ – notebook to redict CategoryID from “Drug + Effect” 
‘Multimodal_FAERS.ipynb’ – notebook for FARES dataset preprocessing and multi-modal ADE detection 

## Setup Instructions
 Clone the repo
git clone <your-repo-link>
repo link : Multimodal-Transformer-Based-Model-for-ADE-Detection
Install Dependencies:
pip install -r requirements.txt
 Run Jupyer Notebook:
jupyter notebook

 Then step by step run all the cells
