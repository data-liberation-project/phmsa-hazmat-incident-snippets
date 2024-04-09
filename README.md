# Python Snippets for PHSMA Hazmat Incident Report Data

The goal of this repository is to help you gain familiarity with the [PHMSA Hazmat Incident Report data](https://github.com/data-liberation-project/phmsa-hazmat-incident-reports) collected by the [Data Liberation Project](https://www.data-liberation-project.org/), with an eye toward understanding the data structure and data quality.

The code in this repository is written in Python and assumes you have some familarity with that programming language.

## Getting started

If you just want to read the code and review the outputs, you can [view this repository's main notebook directly](notebooks/snippets.ipynb).

If you want to run the code yourself, follow these steps:

- Ensure that you have Python 3 installed
- Use [`git clone`](https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository) to copy this repository onto your computer
- `cd` into the repository's main directory
- Run `git submodule update --init --remote --recursive` to pull the latest data into the `phmsa-hazmat-incident-reports/` subdirectory
- Run `make venv` to create a Python virtual environment with the necessary requirements
- Run `source venv/bin/activate` to activate the virtual environment
- Run `jupyter lab` to launch Jupyter
- Within Jupyter, navigate to the `notebooks/snippets.ipynb` notebook

## Contributors

Many thanks to the Data Liberation Project volunteers who have contributed to this repository:

- [@kbathgate](https://github.com/kbathgate)


## Licensing

This repository's code is available under the [MIT License terms](https://opensource.org/license/mit/).

## Questions?

File an issue in this repository or email Jeremy Singer-Vine at `jsvine@gmail.com`.
