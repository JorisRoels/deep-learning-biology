# Deep Learning for Biology
This repository contains the notebooks for the exercise sessions of the VIB [Deep Learning for Biology](https://training.vib.be/all-trainings/deep-learning-biology) workshop. 

You can try out these exercises in the cloud for free by using [Google Colab](https://colab.research.google.com/). Alternatively, you can also run them locally by running the instructions below. Please keep in mind that the exercises can be time-consuming without a [CUDA capable device](https://developer.nvidia.com/cuda-gpus). 

## Installation

Follow these instruction if you want to run the notebooks contained in this repository using either Google Colab or a local [Jupyter Lab](https://jupyterlab.readthedocs.io/en/stable/).

### Google Colab

Navigate to the assignments folder on GitHub: [https://github.com/JorisRoels/deep-learning-biology/tree/main/exercises/assignments](https://github.com/JorisRoels/deep-learning-biology/tree/main/exercises/assignments).

You can preview the notebooks by clicking on them.
Open them in Colab by clicking the 'Open in Colab' badge in the GitHub notebook preview. This is simply a URL similar to the GitHub file location `https://colab.research.google.com/github/{GITHUB_URL}` e.g. [https://colab.research.google.com/github/JorisRoels/deep-learning-biology/blob/main/exercises/assignments/dlb-0-intro-pytorch.ipynb](https://colab.research.google.com/github/JorisRoels/deep-learning-biology/blob/main/exercises/assignments/dlb-0-intro-pytorch.ipynb).

Optionally follow the Google Colab [tutorials](https://colab.research.google.com) for more information. 

Make sure you work on the assignments using a GPU accellerated runtime:

- In Colab, click on `Connect` in the upper-right bar to connect to a free runtime.
- In the top navigation bar, go to `Runtime > Change runtime type`
    - Make sure `Hardware accelerator` is set to `GPU`
- There is a limit to your total active sessions
    - Manage sessions using `Runtime > Manage sessions`
- If you close your session, all data will be lost. Should you need to, there are options to save your notebook
    - Save a copy locally using `File > Download > Download .ipynb`
    - Save a copy to Google Drive / GitHub using other options in the `File` menu

### Local Jupyter Lab

Clone this repository locally using `git`

```
git clone https://github.com/JorisRoels/deep-learning-biology.git
```

`cd` into the project directory
```
cd deep-learning-biology
```

Install the environment using [Conda](https://docs.conda.io/en/latest/miniconda.html)

```
conda env update -f environment.yaml --prune
```

The same command can also be used to update the `deep-learning-biology` Conda enviroment should you edit the dependencies in the file `enviroment.yaml`. See [the documentation](https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html) for more info.

Go into the virtual enviroment and start Jupyter Lab
```
conda activate deep-learning-biology
jupyter lab
```

Navigate the folder `./exercises/assignments` and solve them in order.