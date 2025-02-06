# Example Jupyter Notebooks

This repository contains a collection of Jupyter notebooks that serve as an introduction to the new alpha version of the pairinteraction library.

To install the alpha version of the new `pairinteraction` version, you can run the following command:

```bash
pip install --index-url https://test.pypi.org/simple/ --extra-index-url https://pypi.org/simple/ pairinteraction
```

We recommend using a virtual environment to install the package in a python environment (we support python 3.9 - 3.13),
e.g. you can use [uv](https://docs.astral.sh/uv/getting-started/installation/) (available for linux, mac and windows).

Small examples of installing uv and creating a virtual environment with uv are given below:

## Windows
Install uv following the instructions on the [uv website](https://docs.astral.sh/uv/getting-started/installation/), i.e. run the following command in the powershell:
```powershell
powershell -ExecutionPolicy ByPass -c "irm https://astral.sh/uv/install.ps1 | iex"
```
To have access to the `uv` command in the command prompt, you might have to restart your system, then create a virtual environment with the following command:
```powershell
uv venv example_venv
```
To now activate the virtual environment, you have to run the following commands in the powershell (the first command is necessary to allow activating the virtual environment).
In addition, you have to install pip in the virtual environment via uv, as it is not installed by default:
```powershell
Set-ExecutionPolicy Unrestricted -Scope Process
example_venv/Scripts/activate
uv pip install pip
```
Finally, you can install the package via:
```powershell
pip install --index-url https://test.pypi.org/simple/ --extra-index-url https://pypi.org/simple/ pairinteraction
```

## Linux / MacOS
Install uv following the instructions on the [uv website](https://docs.astral.sh/uv/getting-started/installation/), i.e. run the following command in the terminal:
```bash
curl -LsSf https://astral.sh/uv/install.sh | sh
```
Then run the following commands in the terminal to create and activate a virtual environment, and install the package via pip:
```bash
uv venv example_venv
. example_venv/bin/activate
uv pip install pip
pip install --index-url https://test.pypi.org/simple/ --extra-index-url https://pypi.org/simple/ pairinteraction
```
To create an environment with a specific python version, you can add e.g. the `--python=3.11` flag to the `uv venv` command.
