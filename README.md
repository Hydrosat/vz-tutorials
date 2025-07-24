# Hydrosat How-To Guides

A collection of examples showing how users can work with Hydrosat data via STAC API.

## Table of Contents

- [Overview](#overview)
- [Environment Setup](#environment-setup)
- [Running the Notebooks](#running-the-notebooks)
- [Contact](#contact)

---

## Overview

This repository contains interactive Jupyter notebooks that demonstrate the following:
1. All-in-one guide to getting started with Hydrosat data (```vz-quickstart.ipynb```)
2. Using different search filters to find data (```searching-the-catalog.ipynb```)
3. Preparing data for analysis (```vz-processing.ipynb```)
4. Using the cloud and QA masks (```using-the-cloud-mask.ipynb```)

---

## Environment Setup

You can set up your environment using either Conda or pip:

### Option 1: Using Conda

Make sure you have [Miniconda](https://docs.conda.io/en/latest/miniconda.html) or [Anaconda](https://www.anaconda.com/) installed.

```bash
conda env create -f env.yaml
conda activate env
```
---

### Option 2: Using pip

```bash
python -m venv env
source env/bin/activate  # On Windows: env\Scripts\activate
pip install -r requirements.txt
```

---

## Running the Notebooks

Once the environment is active, open your IDE of choice and start exploring the notebooks.

With VSCode:
```bash
code .
```

With Jupyter Lab:
```bash
jupyter lab
```

With Spyder:
```bash
spyder
```

---

## Contact

You can reach us at <support@hydrosat.com>.

Learn more about Hydrosat at www.hydrosat.com.
