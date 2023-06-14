# Machine Learning Beginning Course

Класичний вступний курс із сучасного Machine Learning з акцентом на практику.

https://prjctr.com/course/machine-learning-basics

## Installation

0. Check your `python` and `pip` verison. You need to use python 3.6 or higher

    `pip --version`

1. Install [Jupyter](https://jupyter.org/install)

    `pip install jupyter`
2. Install [virtual environment](https://packaging.python.org/guides/installing-using-pip-and-virtual-environments/)

    `pip install virtualenv`

3. Create new virtual environment in repo folder

    `cd machine_learning_projector`

    `python -m venv venv`

4. Activate virtual environment

    `source venv/bin/activate`

5. Install packages

    `pip install numpy pandas matplotlib scikit-learn`

6. Create kernel

    `pip install ipykernel`

    `ipython kernel install --user --name=ml-course`

7. Deactivate environment

    `deactivate`

## Usage

1. Start jupyter

    `cd machine_learning_projector`

    `jupyter notebook`

2. Select `ml-course` kernel
