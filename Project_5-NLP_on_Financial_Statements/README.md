# AI-for-Trading Project 5: NLP on Financial Statements

## Overview
This project involves performing Natural Language Processing (NLP) analysis on 10-K financial statements. The goal is to parse, process, and analyze these documents to extract meaningful insights.

## Installation

### Requirements
- Python 3.x
- Pandas
- Numpy

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install the required packages.

```bash
pip install pandas numpy
```

## Usage

To run this project, follow these steps:

1. **Load and Install Packages**: Ensure all required packages are installed and imported.

2. **Download NLP Corpora**: You will need the stopwords corpus for removing stopwords and wordnet for lemmatizing. Ensure you have these resources available.

3. **Download 10-Ks**: The project requires 10-K documents which can be downloaded using the CIK numbers provided or by adding additional CIKs to the `additional_cik` dictionary.

4. **Run Analysis**: Execute the functions as instructed in the notebook to perform NLP analysis.

```python
# Example function call
analyze_10k(document)
```

## Contributing
Contributions to this project are welcome. Please ensure to update tests as appropriate.