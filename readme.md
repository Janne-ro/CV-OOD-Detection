# Advanced Out-of-Distribution Detection for Multi-Class Classification

**Final Project for the Course Computer Vision tought at La Sapienza 2025**  
Name: Janne Rotter  
Matricula: 2223529  
Email: rotter.2223529@studenti.uniroma1.it

## Goal of the project
This project first trains an Efficient-Net-B0 on the Food-101 datasets using transfer learning. Later on multiple methods for OOD-Detection are implemented and evaluated based on AUROC and FPR95. Additionally, it is investigated wheter model performance significantly influences the performance of these methods. 

## Methods Implemented
The following methods were implemented:
* MSP
* ODIN
* Energy score
* GradNorm
* FeatureNorm

## Structure of the Repo
This repository includes the following:
* The notebook originally developed for use in Google Colab 
* The final presentation for the project
* A folder including the weights of the learned models 

## Used Datasets 
Overall I used the following datasets:
* [Food-101 dataset](https://www.tensorflow.org/datasets/catalog/food101) (ID data)
* [SVHN dataset](http://ufldl.stanford.edu/housenumbers/) (OOD data)
* [Texture DTD dataset](https://www.tensorflow.org/datasets/catalog/dtd) (OOD data)
* [Place365 dataset](https://www.tensorflow.org/datasets/catalog/places365_small) (OOD data)

## How to run
- The notebook is designed to be run on Google Colab.
- Required libraries can be extracted from the import cell of the notebook
- Simply open the notebook in Colab and run the cells sequentially.