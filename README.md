# RSMAN
Source code for NAACL 2022 paper: Relation-Specific Attentions over Entity Mentions for Enhanced Document-Level Relation Extraction
## Introduction
This is the implementation of the **RSMAN** (**R**elation-**S**pecific **M**ention **A**ttention **N**etwork) with [**SSAN**](https://arxiv.org/abs/2102.10249) as the backbone model. **RSMAN** is easy to be plugged into other different backbone models to enhance them and here we take **SSAN** for example. Part of the code is borrowed from https://github.com/BenfengXu/SSAN, and we really appreciate it.
<div  align="center">  
<img src="./RSMAN.png" width = "400" height = "350" align=center />
</div>  

## Requirements
* python==3.6
* pytorch==1.4.0
* transformers==2.7.0

## Dataset
* [DocRED](https://github.com/thunlp/DocRED)
* [DWIE](https://github.com/klimzaporojets/DWIE)
* Note that you should process DWIE to fit the same format as DocRED. Put the dataset into the directory `./data`.


## Train
