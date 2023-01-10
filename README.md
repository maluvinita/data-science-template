# Cookiecutter Data Science

_A standardized but flexible project structure for doing and sharing data science work._

## Project structure
```bash
.
├── config                      
│   ├── main.yaml                   # Main configuration file
├── data            
│   ├── final                       # data after training the model
│   ├── processed                   # data after processing
│   ├── raw                         # raw data
├── docs                            # documentation for your project
├── .gitignore                      # ignore files that cannot commit to Git
├── models                          # store models
├── notebooks                       # store notebooks
├── .pre-commit-config.yaml         # configurations for pre-commit
├── pyproject.toml                  # dependencies for poetry
├── README.md                       # describe your project
├── src                             # store source code
│   ├── __init__.py                 # make src a Python module 
└── tests                           # store tests
    ├── __init__.py                 # make tests a Python module 
```
### Requirements to use the cookiecutter-project template:
-----------
 - Python 3.8+
``` bash
$ pip install cookiecutter
```
### To start a new project, run:
------------

    cookiecutter https://github.com/maluvinita/data-science-template
