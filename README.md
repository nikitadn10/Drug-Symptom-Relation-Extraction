# Biomedical Drug-Disease Relation Extraction

Fine-tuned BioBERT for 3-class relation extraction (TREATS / CAUSES / NO_RELATION) 
from clinical text using BC5CDR corpus (1,500 annotated PubMed abstracts).

## Tech Stack
- BioBERT (dmis-lab/biobert-base-cased-v1.2)
- spaCy dependency parsing (shortest path)
- BC5CDR dataset (BioCreative V, NCBI)
- HuggingFace Transformers, PyTorch

## Results
- TREATS F1: 0.81
- Dataset: 1,978 training samples (balanced)

## Run
Open in Google Colab with T4 GPU and run all cells.
