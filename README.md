# Machine Learning Notebooks

The goal of this repository is to re-implement the notebooks from [Hands-on Machine Learning with Scikit-Learn, Keras and TensorFlow](https://www.oreilly.com/library/view/hands-on-machine-learning/9781492032632/) for practical learning, practice and referance purposes. The notebooks go over tools like Scikit-Learn, Keras & TensorFlow.

<img src="https://images-na.ssl-images-amazon.com/images/I/51aqYc1QyrL._SX379_BO1,204,203,200_.jpg" title="book" width="150" />

The original implementation of the notebooks are housed at [ageron/handson-ml2](https://github.com/ageron/handson-ml2).

## Quick Start

### How to run the projects locally

Start by installing [Anaconda](https://www.anaconda.com/distribution/) (or [Miniconda](https://docs.conda.io/en/latest/miniconda.html)), [git](https://git-scm.com/downloads), and if you have a TensorFlow-compatible GPU, install the [GPU driver](https://www.nvidia.com/Download/index.aspx), as well as the appropriate version of CUDA and cuDNN (see TensorFlow's documentation for more details).

Next, clone this project by opening a terminal and typing the following commands (do not type the first `$` signs on each line, they just indicate that these are terminal commands):

    $ git clone https://github.com/ageron/Hands-On-Machine-Learning-Notebooks.git
    $ cd hands-on-machine-learning-notebooks

#### Install using Anaconda

Next, run the following commands:

    $ conda env create -f environment.yml
    $ conda activate tf2
    $ python -m ipykernel install --user --name=python3

Finally, start Jupyter:

    $ jupyter notebook

#### Install using python venv module

    $ python -m venv .env
    $ source .env/bin/activate #MacOs
    $ .env/scripts/activate #Windows
