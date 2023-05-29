# categorical-feature-encoding
Understanding categorical feature encodings

# data
Dowload the data -- `sample_submission.csv`, `test.csv`, `train.csv` from https://www.kaggle.com/competitions/cat-in-the-dat-ii and copy them into `data/input` folder

# Managing package dependency
We are using `poetry` -- https://python-poetry.org/docs/ to manage package dependencies and also to manage the virtual environment. 

Note:
1. We need to keep the `poetry.lock` and `pyproject.toml` checked in and updated in the repository. Every time to you install a package, the `poetry.lock` and `pyproject.toml` files will be automatically updated and we need to push these files to repository.
