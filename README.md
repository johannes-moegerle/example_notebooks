# Example Jupyter Notebooks

This repository contains a collection of Jupyter notebooks that serve as an introduction to the new alpha version of the pairinteraction library.

To install the alpha version of the new pairinteraction version, you can run the following command:

```bash
pip install --index-url https://test.pypi.org/simple/ --extra-index-url https://pypi.org/simple/ pairinteraction-next
```

Note this is currently only possible for python 3.9.
We recommend using a virtual environment to install the package in a python 3.9 environment.

E.g. you can install uv (see [here](https://docs.astral.sh/uv/getting-started/installation/)), and then create and activate a virtual environment with:

```bash
uv venv example_venv --python=3.9
. example_venv/bin/activate
uv pip install --index-url https://test.pypi.org/simple/ --extra-index-url https://pypi.org/simple/ pairinteraction-next
```

(For windows you might have to use `uv.exe` instead of `uv` or if you have installed uv via pip you can also run `python -m uv` instead of `uv`. Alternatively you can also use [conda](https://anaconda.org/anaconda/conda) to create a virtual environment).
