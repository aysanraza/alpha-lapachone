# Obesity Controller
The Logistic regression algorithm trained on Proteomics dataset of alpha-lapachone for screening the potential drug targets in human adipogenesis pathway.

## Introduction

Alpha-lapachone is a flavonoid compound that is found in the bark of lapacho trees. It has been shown to have a variety of biological activities, including anti-cancer, anti-microbial, and anti-inflammatory effects.

This repository contains a Jupyter Notebook file that describes a study on the potential anti-obesity effects of alpha-lapachone. The study involved training a logistic regression model to predict whether a given protein is a target of alpha-lapachone. The model was trained on a dataset of 42 proteins that are known to be targets of alpha-lapachone and 83 random proteins. The model achieved the following evaluation metrics:

* Accuracy: 86%
* Precision: 87%
* Recall: 100%
* F1 Score: 93%
* AUC: 82%

The trained model was then used to screen a dataset of 83 proteins that are involved in the human adipogenesis pathway. Two proteins, CD36 and ADIRF, were found to have similar tripeptides to the proteins that are known to be targets of alpha-lapachone. CD36 is a part of the basic immune system, while ADIRF is a basic adipogenesis gene that is involved in differentiation and stimulates transcription initiation of master adipogenesis factors like PPARG and CEBPA at early stages of preadipocyte differentiation.

These findings suggest that alpha-lapachone may have anti-obesity characteristics through regulating the adipogenesis and immune related responses.

## Installation

To run the Jupyter Notebook file in this repository, you will need to have the following software installed:

* Python 3
* Jupyter Notebook
* NumPy
* Pandas
* Scikit-Learn

You can install these dependencies using the following command:

`pip install jupyter numpy pandas scikit-learn`

Once the dependencies are installed, you can clone the repository using the following command:

`git clone https://github.com/aysanraza/obesity-controller.git`

## Usage

To use the obesity controller, you will need to open the `obesity_controller.ipynb` file in Jupyter Notebook.

The Jupyter Notebook file contains a step-by-step guide to running the logistic regression model and screening the human adipogenesis pathway. To run the model, simply follow the instructions in the notebook.

Once the model has been run, you can view the results in the notebook. The results include the following:

* A list of the proteins that were predicted to be targets of alpha-lapachone
* A plot of the ROC curve for the model
* A list of the genes that were found to have similar tripeptides to the proteins that are known to be targets of alpha-lapachone


## Version History
* 0.1
  * Initial Release

## License
This project is licensed under the  MIT license - see the LICENSE.md file for details

## Authors
* Ahsan Raza
  * aysanraza@gmail.com
  * [Linkedin](https://www.linkedin.com/in/ahsan-raza-0510b1128/)
