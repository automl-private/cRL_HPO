# cRL_HPO

## Installation
If you do not have a virtual environment, we recommend to create and activate a virtual environment (e.g. Anaconda) first.
We recommend to use python 3.9 under Linux.

Then, install CARL (https://github.com/automl/CARL#installation) in your workdir:
```
git clone https://github.com/automl/CARL.git --recursive
cd CARL
pip install gym[box2d]
pip install -e .
```

Now, please clone this repo and install.
Requirements:
ray[tune]
stable_baselines3
sb3-contrib
