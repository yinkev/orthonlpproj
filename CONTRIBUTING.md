# Contributing

This repository contains a small medical NLP notebook workflow. Contributions should improve reproducibility, notebook clarity, dependency hygiene, or data handling.

## Good Contributions

- Notebook cleanup that preserves the learning flow.
- Dependency fixes for fresh environments.
- Better setup notes for NLTK, spaCy, Biopython, or Jupyter.
- Small sample-data improvements using public, non-sensitive sources.

## Development

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
python3 -m json.tool 01-Basic-Text-Processing.ipynb >/dev/null
```

Do not commit private clinical data, credentials, or large generated artifacts.

## Pull Requests

Keep PRs focused and include whether you ran the notebook, validated the notebook JSON, or only changed documentation.
