# Overview

...

# The example notebook

To get you started we have an example [Juptyer](https://jupyter.org) notebook with some basic data exploration for the run recordings. Jupyter is a popular data science environment built around the idea of a 'notebook', which is a portable collection of code along with documentation. Even though we've used Jupyter, feel free to use other tools and languages for this challenge if you prefer.

## Running the notebook locally

### Prerequisites

Python 3.

### Virtualenv

Using Python VirtualEnv is optional but recommended.

First create the virtual environment:

```sh
python -m venv env
```

Then to activate:

```sh
source env/bin/activate
```

You can deactivate the environment any time with `deactivate`.

### Install dependencies

To install Python dependencies:

```sh
pip install -r requirements.txt
```

### Run the notebook

Activate the virtual environment if you haven't already done so by running `source env/bin/activate`. Run `jupyter notebook`; Jupyter should launch as a server and open in a browser (if not, just navigate to `http://localhost:8888/tree` or the URL reported in the terminal when Jupyter started).

With Jupyter running you can navigate to `notebooks/data-exploration.ipynb`. You can execute all the code in the notebook at once, or step through it cell-by-cell.

## Running the notebook on Google Colab

TODO
