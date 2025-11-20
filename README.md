# jelitaw_diffusion2d

## Instructions for other students

If you plan on also learning the used techniques for yourself, then please follow the instructions in [pypi_exercise.md](https://github.com/Simulation-Software-Engineering/Lecture-Material/blob/main/03_building_and_packaging/pypi_exercise.md).

The code used in this exercise is based on [Chapter 7 of the book "Learning Scientific Programming with Python"](https://scipython.com/book/chapter-7-matplotlib/examples/the-two-dimensional-diffusion-equation/).

## Description

This package provides a simple two-dimensional diffusion simulator based on a finite-difference discretization of the heat equation. It is used as an example to learn building and packaging.

## Installing the package

Run the following command; preferably in a venv where pip is installed:

```
pip install --extra-index-url https://test.pypi.org/simple/ jelitaw_diffusion2d
```

## Running this package

After installation, it can be used with:

```
from jelitaw_diffusion2d import diffusion2d

diffusion2d.solve() # use default parameters
# or with custom parameters, e.g.
diffusion2d.solve(dx=0.2, dy=0.2, D=1.6)

```

## Citing

This repo was built following the exercise on the [Simulation-Software-Engineering](https://github.com/Simulation-Software-Engineering/Lecture-Material/blob/main/03_building_and_packaging/pypi_exercise.md) GitHub page.
