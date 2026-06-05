# Orthopedic NLP Project

Notebook-based exploration of basic medical NLP workflows using PubMed abstracts related to total knee arthroplasty.

## Contents

- `01-Basic-Text-Processing.ipynb` - tokenization, normalization, lemmatization, PubMed retrieval, and simple text processing examples.
- `pubmed_sample_tka_10.csv` - small sample dataset of PubMed metadata and abstracts used by the notebook.
- `requirements.txt` - pinned Python/Jupyter/NLP dependencies.

## Setup

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install --upgrade pip
pip install -r requirements.txt
jupyter lab
```

The notebook uses NLTK, spaCy, Biopython, pandas, and common Python NLP tooling. PubMed requests should set a real NCBI Entrez email before running live retrieval cells.

## License

MIT
