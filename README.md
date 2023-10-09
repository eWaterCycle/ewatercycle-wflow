# eWaterCycle plugin for wflow hydrological model

[![Research Software Directory Badge](https://img.shields.io/badge/rsd-00a3e3.svg)](https://www.research-software.nl/software/ewatercycle-wflow)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.8420109.svg)](https://doi.org/10.5281/zenodo.8420109)
[![PyPI](https://img.shields.io/pypi/v/ewatercycle-wflow)](https://pypi.org/project/ewatercycle-wflow/)

wflow plugin for [eWatercycle](https://ewatercycle.readthedocs.io/).

wflow documentation at https://wflow.readthedocs.io/ .

## Installation

eWaterCycle must be installed in a [mamba](https://conda-forge.org/miniforge/) environment. The environment can be created with

```console
wget https://raw.githubusercontent.com/eWaterCycle/ewatercycle/main/environment.yml
mamba env create --name ewatercycle-wflow --file environment.yml
conda activate ewatercycle-wflow
```

Install this package alongside your eWaterCycle installation

```console
pip install ewatercycle-wflow
```

Then Wflow becomes available as one of the eWaterCycle models

```python
from ewatercycle.models import Wflow
```

## Usage

Usage of wflow forcing generation and model execution is shown in 
[docs/generate_forcing.ipynb](https://github.com/eWaterCycle/ewatercycle-wflow/tree/main/docs/generate_forcing.ipynb) and [docs/model.ipynb](https://github.com/eWaterCycle/ewatercycle-wflow/tree/main/docs/model.ipynb) respectively.

## License

`ewatercycle-wflow` is distributed under the terms of the [Apache-2.0](https://spdx.org/licenses/Apache-2.0.html) license.
