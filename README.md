# artificial networks explorations

## About
A repo where to explore
- neural network architectures;
- varied tasks;
- task-specific data generation;
- data processing;
- training methods;
- tools exploration.

## Organization

Each exploration topic has its own folder named after it with `ipynb` notebooks, each focusing on a subject-matter:
- [architectures](notebooks/architectures), focusing on different network layers and architectures;
- [training](notebooks/training), focusing on training methods;
- [tasks](notebooks/tasks), focusing on a variety of tasks;
- [data](notebooks/data), focusing on data generation, and processing for different types of data;
- [pytorch](notebooks/pytorch), focusing on PyTorch as a tool;

Given that the topics are interconnected, they have no specific order. Each topic also has an `overviewm.md` file with words.

The accompanying source code is in [src](src) folder.

It's all written in Python, using PyTorch.

## Setup

Having a `Python 3.11+` environment, 

The source code can be installed as a package with
```bash
pip install . # pass -e flag for editable install
```

One can also find the dependencies in
- [requirements.txt](requirements.txt) for a versioned snapshot of all dependencies;
- [requirements-unversioned.txt](requirements-unversioned.txt) for the un-versioned core dependencies.
- [requirements-dev.txt](requirements-dev.txt) for the development dependencies.

