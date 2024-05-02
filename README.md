# CPE Prediction for Marketing Campaigns

## Installation

This repository uses `poetry` as the dependency manager and virtual environment.
Please refer to this [page](https://python-poetry.org/docs/) on how to install poetry.

After installing `poetry`, run the following command to install the dependencies:

```bash
$ poetry install --no-root
$ poetry run spacy download en_core_web_sm
```

Now to activate the virtual environment on your shell:

```bash
$ poetry shell
```

## Running jupyter

With the virtual environment activated, run the following command to start the jupyter server:

```bash
$ jupyter lab
```

Inside the jupyter lab search for the notebook `explore.ipynb`.