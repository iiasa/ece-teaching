# Teaching and learning material

Copyright (c) 2021 IIASA

![License](https://img.shields.io/github/license/iiasa/teaching)

## Overview

This repository contains teaching and learning materials with different formats like courses, seminars, code-and-tell, workshops etc.). You can find the documentary [here](https://iiasateaching.readthedocs.io/en/latest/)

## Recommendations

We recommend that you follow the [numpydoc](https://numpydoc.readthedocs.io)
docstring formatting guide.

Looking for more best-practice tools for scientific software development?
Take a look at the [cookiecutter-hypermodern-python](https://github.com/cjolowicz/cookiecutter-hypermodern-python) repository!

## Installation

Install the package including the requirements for building the docs.

    pip install --editable .[doc]

## Building the docs

Run Sphinx to build the docs!

    make --directory=doc html

The rendered html pages will be located in `doc/build/html/index.html`.
