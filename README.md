# Data Version Control for Machine Learning Projects

Data version Control (DVC) is a version control system that tracks large data sets and machine learning models with the aim to make ML models shareable and reproducible.

More information about DVC can be found on the official webpage <https://dvc.org/>

This repository shows you how to integrate dvc in your projects and hopefully you will not need to worry about where to store your data sets and models because github does not support more than 100mb.

![alt text](image/model-versioning-diagram.png)
source: image taken from [dvc](https://dvc.org/doc/use-cases/data-and-model-files-versioning)

## Get Started
In this guide we are going to focus on dataset/model versioning in simple steps, reproducibility will be released later in this guide, so stay tunned.

First clone this or any other repository, because dvc works on top of git repositories.

```bash
git clone https://github.com/jwilliamn/dvcML.git
cd dvcML
```

## 1. Install DVC
Once we have our repo, we install DVC. It is a good practice to install in an isolated environment i.e. `virtualenv` or `conda`.

```bash
pip install dvc
```

## 2. Initialize DVC
On the fresh repository, we initialize as follows.

```bash
dvc init
git commit -m "DVC initialized"
```
