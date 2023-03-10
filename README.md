# Reproducing Random Forest Efficacy in Detecting Port Scanning

This repository contains all the necessary files to rebuilt this project.

- [Content of this repository](#content-of-this-repository)
- [Pre-requisites](#pre-requisites)
- [Contribute to the framework](#contribute)
- [How to cite](#how-to-cite)

## Content of this repository
* `full_data.csv`: contains pre-processed 'bonafide' dataset per Bertoli et a. (2021).
* `rf-detect.ipynb`: contains basic random forest implementation with the four trial hyperparameter sets.
* `requirements.txt`: contains the output from `pip freeze > requirements.txt`

## Pre-requisites
First, we use a native Python virtual environment, not an Anaconda environment. To do the same, use:

```
python -m venv venv
source venv/bin/activate
ipython kernel install --user --name=venv
```

Then: `pip install -r requirements.txt`

After, running `jupyter notebook` will allow you to select the `venv`.

## Contribute to the framework
To contribute with the framework, you can use the Issues and Pull Requests from Github platform.

## How to cite
@article{pittman2023,  
  doi = {10.48550/ARXIV.2302.09317},  
  url = {https://arxiv.org/abs/2302.09317},  
  author = {Pittman, Jason M.},  
  keywords = {Cryptography and Security (cs.CR), Machine Learning (cs.LG), FOS: Computer and information sciences, FOS: Computer and information sciences},  
  title = {Reproducing Random Forest Efficacy in Detecting Port Scanning},  
  publisher = {arXiv},  
  year = {2023},  
}

