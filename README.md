![interrogate](badges/interrogate_badge.svg)

# 🚦 Traffic Network MARL

## Overview

Using multi-agent RL to optimise a simulated small-scale traffic network. This is initialy conducted in Python and then replicated in C++ to compare training times. If possible, training iterations of the simulation will be visualised in C++ to show how the chosen model works.

## Usage

### Development

#### Python

To prepare a suitable python enviroment for development, this project uses `poetry` for package management. This can be instantiated easily noting that you need a python version of `3.10.0`.

```bash
# From root project directory
python -m pip install poetry
python -m pip install torch
python -m poetry install --no-root --with dev
```

### Releases

Todo.
