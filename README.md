# Overview

For this challenge the Fuzzy Labs have competed in a virtual race while wearing some prototype hardware on their shoes, affectionately known as the [_wearable, my foot!_](http://wearablemyfoot.tech) device.

This repository contains the data files recorded by the runners participating in the race. Specifically, accelerometer and gyroscope readings. There's also a Jupyter notebook with some basic data exploration steps.

## Rules of the race

Runners run for a _fixed duration of time_: `120` seconds. They each run a course of their choosing, although trying to keep it somewhat straight and level. The winner is whoever covers the most _distance_ in the allowed time.

To make the data easier to deal with, runners stand still for a short period pf time just before they begin running, and again after they stop.

## Challenges

* For each runner, draw a distance over time graph.
* For each runner, draw a graph showing the steepness of their ascent (their gradient) over time.
* Simulate the race by visualising distance travelled throughout time.

# The data files

There are three data files in the [data](data) directory, recorded by:

* Tom
* Misha
* Matt

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
