# AWS SageMaker Playground

## Requirement
- Python >= 3.6.x
- virtualenv
- [kaggle account](https://github.com/Kaggle/kaggle-api)
- [xgboost](https://www.lfd.uci.edu/~gohlke/pythonlibs/) (based on Python version)

## How-to-use
- Always `git pull` to keep in sync with the latest commit
- Create new virtualenv `virtualenv env`
- `source venv/bin/activate` (Linux) or `venv/Scripts/activate` (Windows) to use this virtual environment
- `pip install -r requirement.txt`
- If you failed to install xgboost, download xgboost based on your Python version, OS type, and OS bit type

## How to use Kaggle API
- create Kaggle account
- [follow this tutorial ](https://github.com/Kaggle/kaggle-api)
- go to the competition page > data > copy the command `kaggle competitions download -c <name-of-competition>`