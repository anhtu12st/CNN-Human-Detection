# Image human detection

## Table of Contents

1. [Description](#description)
2. [Getting Started](#getting_started)
   1. [Dependencies](#dependencies)
   2. [Files Structures](#files_structures)
   3. [Executing Program](#execution)
3. [Authors](#authors)
4. [License](#license)
5. [Acknowledgement](#acknowledgement)

<a name="description"></a>
## Description

In more recent deep learning based systems, the majority of the problems inherent in early human identification approaches are considerably minimized. The introduction of these fixes comes at the expense of extra calculations. Modern machine learning frameworks can give these enhanced outcomes with comparable frame rates, albeit, in the presence of GPU acceleration.

This project contains the following parts:

1. Processing data, building an ETL pipeline to extract data from INRIAPerson dataset.
2. Build a pipeline to train the and classify images.

<a name="getting_started"></a>
## Getting Started

<a name="dependencies"></a>
### Dependencies

- Python 3.7+
- NumPy
- OpenCV
- Keras
- TensorFlow
- sklearn

<a name="files_structures"></a>
### Files Structures

- [main.ipynb](./main.ipynb): Processing and training model
- [README.md](./README.md)

<a name="execution"></a>
### Executing Program:

Open [main.ipynb](./main.ipynb) and run with google colab or jupyter notebooks.

<a name="authors"></a>
## Authors
[anhtu12st](https://github.com/anhtu12st)

<a name="license"></a>
## License
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

<a name="acknowledgement"></a>
## Acknowledgements

* [Udacity](https://www.udacity.com/) provides course for Data Scientists
* [Figure Eight](https://www.figure-eight.com/) provides the relevant dataset
