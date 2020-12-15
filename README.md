# Deep Learning for Biology
This repository contains the notebooks for the exercise sessions of the VIB [Deep Learning for Biology](https://training.vib.be/all-trainings/deep-learning-biology) workshop. 

You can try out these exercises by uploading them to [Google Colab](https://colab.research.google.com/). Alternatively, you can also run them locally by running the instructions below. Please keep in mind that the exercises can be time-consuming without a [CUDA capable device](https://developer.nvidia.com/cuda-gpus). 

## Installation

Follow these instruction if you want to run the notebooks contained in this repository.

Start by creating a Python 3 environment with conda, pipenv, virtualenv ...
```
conda create -n deep-learning-biology python=3
conda activate deep-learning-biology
```
Install the dependencies with `pip`: 
```
pip install -r requirements.txt
```
`cd` into the assignments directory and start jupyter lab to solve the exercises: 
```
cd deep-learning-biology/exercises/assignments
jupyter lab
```
