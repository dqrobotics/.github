## DQRobotics

DQ Robotics is a standalone open-source [(LGPLv3)](https://www.gnu.org/licenses/lgpl-3.0.html) library for robot modelling and control. It provides [dual quaternion algebra](http://en.wikipedia.org/wiki/Dual_quaternion) and kinematic calculation algorithms in Python3, Matlab, and C++11.



### Quick Start (Python)

#### User-wide installation 

If you have no idea what a virtual enviroment means, this is probably for you.

```bash
python3 -m pip install --user dqrobotics
```

#### Isolated installation

It is a good practice to isolate projects using `venv` whenever you can.

```bash
python3 -m venv venv
source venv/bin/activate
python3 -m pip install dqrobotics
```

### Documentation

Installation instructions for C++11, MATLAB, and interface packages are available at the project's [readthedocs](https://dqroboticsgithubio.readthedocs.io).

### Citation

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