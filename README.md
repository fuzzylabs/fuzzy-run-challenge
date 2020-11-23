# Overview

For this challenge the Fuzzy Labs have competed in a virtual race while wearing some prototype hardware on their shoes, affectionately known as the [_wearable, my foot!_](http://wearablemyfoot.tech) device.

This repository contains the data files recorded by the runners participating in the race. Specifically, accelerometer and gyroscope readings. There's also a Jupyter notebook with some basic data exploration steps.

## Rules of the race

Runners run along a route of their choosing for a _fixed duration of time_: `120` seconds. The winner is whoever covers the most _distance_ in the allowed time.

To make the data easier to deal with, runners stand still for a short period of time just before they begin running, and again after they stop.

## Challenges

* For each runner, draw a distance over time graph.
* Simulate the race by visualising distance travelled throughout time.
* Who won the race?

# The data files

There are three data files in the [data](data) directory, recorded by:

* Tom
* Misha
* Matt

Each CSV file has six columns:
* time -- time from start of a recording (units: milliseconds)
* aX, aY, aZ -- acceleration measured by the device in X, Y and Z direction respectively (units: g's, where g = 9.8 m/s^2)
* gX, gY, gZ -- rotation measured by the device around X, Y and Z axis respectively (units: degrees/second)  

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
