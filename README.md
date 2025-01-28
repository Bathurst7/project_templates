# ML python project templates
This is the Python ML project templates

### How to use this templates:
1. **data**: This is the data folder
1.1. *raw*: Unprocessed datasets
1.2. *processed*: cleaned and preprocessed dataset
1.3. *external*: third parties dataset
2. notebooks
2.1. `data_analysis.ipynb`
2.2. `model_training.ipynb`
3. **src**
3.1. *data*: Data handling sripts like ETL
3.2. *models*: Training, evaluation scripts
3.3. *utils*: Helper functions
3.4. *visualisations*: Plots, charts
4. **tests**: Unit test for all modules
5. `requirements.txt`: Dependencies
6. `README.md`: Project overview

### Side notes:
* Use pathlib for flexible file handling instead of hardcoded paths
* Follow PEP 8 standards to write clean and professional Python code [this link](https://peps.python.org/pep-0008/)
* Add docstrings to functions and classes to ensure clarity and maintainability
* ***For testing***:
  * Use `pytest` for writing and running tests
  * Use `tox` for testing across multiple python environment