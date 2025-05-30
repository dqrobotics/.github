# DQ Robotics

DQ Robotics is a standalone open-source [(LGPLv3)](https://www.gnu.org/licenses/lgpl-3.0.html) library for robot modelling and control. It provides [dual quaternion algebra](http://en.wikipedia.org/wiki/Dual_quaternion) and kinematic calculation algorithms in Python3, Matlab, and C++11.


## Quick Start (Python)

### Isolated installation

> [!IMPORTANT]
> Most systems will return errors if you do not use a `venv`.

Enviroments such as `pip` have started to enforce the use of isolated enviroments, such as `venv`.

```bash
python3 -m venv venv
source venv/bin/activate
```

### Installing

```bash
python3 -m pip install dqrobotics
```

### Interfaces

> [!IMPORTANT]
> Since [8d8eb88](https://github.com/dqrobotics/python/commit/8d8eb88a33bea49324eae5cdaba4b4b1c5c06a2f), interface packages have been split away from the main library.

If, for instance, `DQ_CoppeliaSimInterfaceZMQ` is needed, instal it as follows.

```bash
python3 -m pip install dqrobotics-interface-coppeliasim-zmq
```

### User-wide installation 

> [!CAUTION]
> If you attempt to install outside of a `venv`, you will get an error in most systems.

```
error: externally-managed-environment
...
hint: See PEP 668 for the detailed specification.
```
See how to address that [here](https://stackoverflow.com/questions/75608323/how-do-i-solve-error-externally-managed-environment-every-time-i-use-pip-3).
 
## Documentation

Installation instructions for C++11, MATLAB, and interface packages are available at the project's [readthedocs](https://dqroboticsgithubio.readthedocs.io).

## Learn

### Kinematic modeling and control of serial-link robotic manipulators using `dqrobotics`: From zero to hero
- [MATLAB Course](https://github.com/dqrobotics/learning-dqrobotics-in-matlab/tree/master/robotic_manipulators).
- [Python Course](https://marinholab.github.io/OpenExecutableBooksRobotics).

## Questions?
Whether you are a beginner or advanced user, you're welcome to ask and answer questions about how to use the library, etc. in our [Q&A section](https://github.com/orgs/dqrobotics/discussions/categories/q-a). Before you ask a new question, we ask members to skim through the forum to verify if their question has already been answered.

## Citation

If you have used this library as part of your academic work, cite it as follows
```bibtex
@article{Adorno-Marinho2020,
archivePrefix = {arXiv},
arxivId = {1910.11612},
author = {Adorno, Bruno Vilhena and  Marinho, Murilo Marques},
doi = {10.1109/MRA.2020.2997920},
eprint = {1910.11612},
issn = {1070-9932},
journal = {IEEE Robotics {\&} Automation Magazine},
pages = {102--116},
month = sep,
volume = {28},
number = {3},
title = {DQ Robotics: A Library for Robot Modeling and Control},
url = {https://ieeexplore.ieee.org/document/9136790/},
year = {2021}
}
```

## Contributing

DQ Robotics is a standalone, fully moderated open-source library, with a core developer team who determines the directions of new developments. To ensure quality control, the team follows a scrict procedure for new pull requests, described [here](https://github.com/dqrobotics/matlab/blob/master/CONTRIBUTING.md). 

Anyone wanting to propose a new modification or introduce new functionality should reach out to the team first, as proposed modifications that do not comply with the development philosophy and style, do not follow the library's architecture, don't introduce a clear and general benefit to the library other than to the person who proposed the modification will likely be rejected with no further discussion.

A good place to initiate such a discussion might be in the [discussion forum](https://github.com/orgs/dqrobotics/discussions).
