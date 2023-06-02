![image](https://github.com/sahil0094/SOAI/assets/31719914/40a3da5d-85d1-42ce-9699-797926f35d7c)


# CNN on MNIST using Pytorch
We are showcasing a modular approach to build CNN model in pytorch on infamous MNIST dataset

# Table of Contents

- [Project Title](#project-title)
- [Table of Contents](#table-of-contents)
- [Libraries used](#installation)
- [Usage](#usage)
- [Development](#development)

# Libraries used
[(Back to top)](#table-of-contents)

```python
from model import *
from utils import *
import torch
import torch.nn as nn
import torch.nn.functional as F
import torch.optim as optim
from torchvision import datasets, transforms
```
# Usage
[(Back to top)](#table-of-contents)

This repo can be used as a repo for beginner to train a cnn model. 
Just donwload the scripts and S5.ipynb and get started in local environment or platofrm like colab,kaggle

# Development
[(Back to top)](#table-of-contents)

We have used pytorch to develop the cnn model here.
Pytorch version 2.0.1+cu118

There are three files being used
1. model.py - This file has the CNN architecture used in this model
2. utils.py - This files consists of utility functions like training the model, testing the results and getting predictions 
3. S5.ipynb - This is the calling file where we are reading the data and calling functions from above scripts



# Contribute
[(Back to top)](#table-of-contents)

We welcome PRs


