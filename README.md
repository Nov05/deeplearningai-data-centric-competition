# deeplearningai-data-centric-competition

https://https-deeplearning-ai.github.io/data-centric-comp/

## About the competition

"A collaboration between DeepLearning.AI and Landing AI, the Data-Centric AI Competition aims to elevate data-centric approaches to improving the performance of machine learning models. In most machine learning competitions, you are asked to build a high-performance model given a fixed dataset. However, machine learning has matured to the point that high-performance model architectures are widely available, while approaches to engineering datasets have lagged. The Data-Centric AI Competition inverts the traditional format and instead asks your to improve a dataset given a fixed model. We will provide you with a dataset to improve by applying data-centric techniques such as fixing incorrect labels, adding examples that represent edge cases, apply data augmentation, etc. Contestants must submit their altered dataset for evaluation by September 4, 2021. (We picked this date because it is the birthday of John McCarthy, who had coined the term artificial intelligence!) The top three winners from each of the two categories (Best Performance Overall and Most Innovative) will be invited to a private event with Andrew Ng to share ideas about how to grow the data-centric movement, and will be highlighted in The Batch and other DeepLearning.AI and Landing AI channels. Good luck!" 

https://worksheets.codalab.org/worksheets/0x7a8721f11e61436e93ac8f76da83f0e6

## Data-Centric AI Competition Submission Guide

### Introduction

A collaboration between DeepLearning.AI and Landing AI, the Data-Centric AI Competition aims to elevate data-centric approaches to improving the performance of machine learning models. In most machine learning competitions, you are asked to build a high-performance model given a fixed dataset. However, machine learning has matured to the point that high-performance model architectures are widely available, while approaches to engineering datasets have lagged. The Data-Centric AI Competition inverts the traditional format and instead asks you to improve a dataset given a fixed model. We will provide you with a dataset to improve by applying data-centric techniques such as fixing incorrect labels, adding examples that represent edge cases, apply data augmentation, etc. Contestants must submit their altered dataset for evaluation by September 4, 2021. (We picked this date because it is the birthday of John McCarthy, who had coined the term artificial intelligence!) The top three winners from each of the two categories (Best Performance Overall and Most Innovative) will be invited to a private event with Andrew Ng to share ideas about how to grow the data-centric movement, and will be highlighted in The Batch and other DeepLearning.AI and Landing AI channels. Good luck!

In this tutorial, we will cover the process of submitting your dataset and results for official evaluation on the Data-Centric AI Competition. Once your dataset has been evaluated officially, your scores will be added to the [leaderboard](https://landing-ai.github.io/data-centric-comp/). Before we begin, please create a CodaLab Worksheets account. Be sure to create a [CodaLab Worksheets account](https://worksheets-dev.codalab.org/), not to be confused with a standard CodaLab account.

#### Rules
* Maximum 5 submissions per week (65 total over the course of the competition)  
* Submission must have less than 10,000 images combined in training and validation  
* Only one CodaLab account per team  

Submissions will be evaluated according to two categories:  
* Best Performance Overall  
* Most Innovative  

#### Getting started

First, download the dataset by clicking into the bundle (click the uuid 0xcea1d7) and press the download button. The dataset contains ~3000 images of handwritten roman numerals 1-10. Your task is to optimize model performance by improving the dataset and making training and validation splits.

Your submission should have the following file structure, with your training and validation data split into different folders. You can rename sample_submission whatever you like, but the file structure and names inside must match the following:   
```
sample_submission/
    train/
        i/
        ii/
        iii/
        iv/
        ...
    val/
        i/
        ii/
        iii/
        iv/
        ...
```



