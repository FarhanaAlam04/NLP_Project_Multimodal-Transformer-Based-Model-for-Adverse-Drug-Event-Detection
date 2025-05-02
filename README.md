# NLP_Project_Multimodal-Transformer-Based-Model-for-Adverse-Drug-Event-Detection

## Project Overview
This project aims to detect Adverse Drug Events (ADEs) from drug-effect pairs and later along with structured data also using a transformer-based approach. We use two different strategies:
- **Part 1**: Multi-label ADE prediction
- **Part 2**: Single-label Effect Category classification
- **Part 3**: Multimodal ADE detection 
## Datasets Used
- ADE-Corpus-V2 : https://huggingface.co/datasets/ade-benchmark-corpus/ade_corpus_v2
- CADEC v2 (SCT) : https://data.csiro.au/collection/csiro:10948
- FAERS structured dataset : https://open.fda.gov/data/faers/
## Files
- ‘NLP_Project_Dataset-Final Cleaning_25CategoryCreation.ipynb’ – ADE+CADEC Dataset  preprocessing, and label Creation<br>
- ‘ADEandCADEC-FinalJoining-Modeling-2.ipynb’ –  predict ADEs from “Drug + Effect”<br>
- ‘ADEandCADDEC-withCategory.ipynb’ – notebook to redict CategoryID from “Drug + Effect” <br>
- ‘Multimodal_FAERS.ipynb’ – notebook for FARES dataset preprocessing and multi-modal ADE detection <br>

## Setup Instructions
* Clone the repo:<br>
  - git clone repo-link <br>
  -repo link : https://github.com/FarhanaAlam04/NLP_Project_Multimodal-Transformer-Based-Model-for-Adverse-Drug-Event-Detection/tree/main <br>
* Install Dependencies:<br>
   - pip install -r requirements.txt<br>
   - pip install torch torchvision torchaudio
   - pip install transformers
   - pip install datasets
   - pip install scikit-learn
   - pip install pandas
   - pip install matplotlib seaborn
   - pip install evaluate 
   - pip install nltk    
   - pip install tqdm
   - pip install jupyter
   - pip install spacy
   - python -m spacy download en_core_web_sm

* Run Jupyer Notebook:<br>
   - jupyter notebook<br>
* Then step by step run all the cells<br>

## HTML File Notice
The .html files in this repository are exported versions of Jupyter Notebooks. These were saved using the File → Save and Export As → HTML option in Jupyter. This allows viewing the notebooks without needing Jupyter itself.

Important Note:
When viewed on GitHub or Google Drive, the HTML files may appear as raw code instead of fully rendered notebooks. If it happens, to properly view the formatted output:

Option 1: Download the .html file and open it in any web browser.

Option 2: View the .ipynb notebook directly using Jupyter or Google Colab.
