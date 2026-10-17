# Kaggle Playground

Notebooks and experiments for Kaggle Playground competitions, linked to my Kaggle profile [chipwa](https://www.kaggle.com/chipwa).

## Layout

- `notebooks/` – exploration and modelling notebooks, one folder per competition
- `data/` – competition data (not tracked in git)
- `submissions/` – generated submission files (not tracked in git)

## Setup

Install the Kaggle CLI and put your API token in `~/.kaggle/access_token` (the older `~/.kaggle/kaggle.json` also works). Both live outside this repo. Never commit them.

## Working with Kaggle

- Pull a notebook with its settings: `kaggle kernels pull chipwa/<notebook> -p notebooks/<competition> -m`
- Push your changes back to Kaggle: `kaggle kernels push -p notebooks/<competition>`
- Download competition data: `kaggle competitions download -c <competition> -p data/<competition>`
