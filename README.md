System requirements

Environments and tools:
macOS Tahoe 26.2
python 3.13.3
homebrew 5.0.16
pipx 1.8.0
jupyterlab 4.4.9

Python packages:
numpy 2.1.3
matplotlib 3.9.3
pandas 2.2.3
scipy 1.14.1
pycpd 2.0.0
oiffile 2024.5.24
pillow 11.0.0
scikit-image 0.25.2

Installation

Codes will run in a macOS environment, and are written in python.

First, please install the homebrew package manager (https://brew.sh), by following its website’s instructions (copy the link into a macOS terminal and excute).

Then, install pipx, by running ‘brew install pipx’ in the terminal, followed by ‘pipx ensurepath’.

After that, install jupyterlab by running ‘pipx install jupyterlab –include-deps’ in the terminal, followed by ‘pipx ensurepath’.

After jupyterlab is installed, close and reopen a new terminal, and run ‘jupyter-lab’ so that a browser will open and load the development environment for python. In the jupyterlab webpage, click on ‘Notebook’ and enter a new cell with ‘pip install package_name’ to install each required python packages.

Demo and instructions for use
