[![author](https://img.shields.io/badge/author-mohd--faizy-red)](https://github.com/mohd-faizy)
![made-with-Markdown](https://img.shields.io/badge/Made%20with-markdown-blue)
![Language](https://img.shields.io/github/languages/top/mohd-faizy/09P_Detecting_COVID_19_with_Chest_X-Ray_using_PyTorch)
![Platform](https://img.shields.io/badge/platform-jupyter%20labs-blue)
![Maintained](https://img.shields.io/maintenance/yes/2020)
![Last Commit](https://img.shields.io/github/last-commit/mohd-faizy/09P_Detecting_COVID_19_with_Chest_X-Ray_using_PyTorch)
[![GitHub issues](https://img.shields.io/github/issues/mohd-faizy/09P_Detecting_COVID_19_with_Chest_X-Ray_using_PyTorch)](https://github.com/mohd-faizy/09P_Detecting_COVID_19_with_Chest_X-Ray_using_PyTorch)
[![Open Source Love svg2](https://badges.frapsoft.com/os/v2/open-source.svg?v=103)](https://opensource.com/resources/what-open-source)
![Stars GitHub](https://img.shields.io/github/stars/mohd-faizy/09P_Detecting_COVID_19_with_Chest_X-Ray_using_PyTorch)
[![GitHub license](https://img.shields.io/github/license/mohd-faizy/09P_Detecting_COVID_19_with_Chest_X-Ray_using_PyTorch)](https://github.com/mohd-faizy/09P_Detecting_COVID_19_with_Chest_X-Ray_using_PyTorch/blob/main/LICENSE)
![Size](https://img.shields.io/github/repo-size/mohd-faizy/09P_Detecting_COVID_19_with_Chest_X-Ray_using_PyTorch)


# __Detecting COVID 19 with Chest X-Ray using PyTorch__

<p align='center'>
  <a href="#">
    <img src='https://github.com/mohd-faizy/DataScience-Projects/blob/main/Projects_png/09_proj.png?raw=true' alt="head_image">
  </a>
</p>

This repository is a case study for detecting COVID-19 with Chest X-Ray using PyTorch from COVID-19 Radiography Dataset on Kaggle

## __Dataset__

__Chest X-ray images for COVID-19 dataset:-__ 

In our current release, there are `1143` COVID-19 `positive images`, `1341` `normal` images and `1345` `viral pneumonia` images.

```python
# Create api key -> account ->Create New Token 
# .json file is genrated 

!pip install -q kaggle
from google.colab import files 
files.upload() #upload kaggle.json
```
```bash
!mkdir -p ~/.kaggle 
!cp kaggle.json ~/.kaggle/ 
!ls ~/.kaggle 
!chmod 600 /root/.kaggle/kaggle.json 

# API Command 
!kaggle datasets download -d tawsifurrahman/covid19-radiography-database

```
## __Objective__

- Create custom Dataset and DataLoader in PyTorch
- Train a ResNet-18 model in PyTorch to perform Image Classification

## Installation
Clone this repository:

```
git clone https://github.com/mohd-faizy/09P_Detecting_COVID_19_with_Chest_X-Ray_using_PyTorch.git

```

or click `Download ZIP` in right panel of repository and extract it.

Open latest version of notebook in __Jupyter Notebook__.

## Project Structure

- Task :zero::one: _Importing the Dataset from Kaggle_
- Task :zero::two: _Importing Libraries_
- Task :zero::three: _Preparing Training and Test Sets_
- Task :zero::four: _Creating Custom Dataset_
- Task :zero::five: _Image Transformations_
- Task :zero::six: _Prepare DataLoader_
- Task :zero::seven: _Data Visualization_
- Task :zero::eight: _Creating the Model_
- Task :zero::nine: _Training the Model_
- Task :one::zero: _Show the Predictions_
- Task :one::one: _Saving the Model_
- Task :one::two: _Inference on a Single Image_

## Model Training Privew 
<p align='center'>
  <a href="#">
    <img src='https://github.com/mohd-faizy/09P_Detecting_COVID_19_with_Chest_X-Ray_using_PyTorch/blob/master/proj_png/01_train.png?raw=true' alt="head_image">
  </a>
</p>

## Prediction Preview

<p align='center'>
  <a href="#">
    <img src='https://github.com/mohd-faizy/09P_Detecting_COVID_19_with_Chest_X-Ray_using_PyTorch/blob/master/proj_png/02_pred.png?raw=true' alt="head_image">
  </a>
</p>


### Connect with me:


[<img align="left" alt="codeSTACKr | Twitter" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/twitter.svg" />][twitter]
[<img align="left" alt="codeSTACKr | LinkedIn" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/linkedin.svg" />][linkedin]
[<img align="left" alt="codeSTACKr.com" width="22px" src="https://raw.githubusercontent.com/iconic/open-iconic/master/svg/globe.svg" />][StackExchange AI]

[twitter]: https://twitter.com/F4izy
[linkedin]: https://www.linkedin.com/in/mohd-faizy/
[StackExchange AI]: https://ai.stackexchange.com/users/36737/cypher


---


![Faizy's github stats](https://github-readme-stats.vercel.app/api?username=mohd-faizy&show_icons=true)


[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=mohd-faizy&layout=compact)](https://github.com/mohd-faizy/github-readme-stats)