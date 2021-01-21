# Global wheat detection

[![License](http://img.shields.io/badge/license-MIT-green.svg?style=flat)](https://github.com/Solvve/ml_wheat_object_detection/blob/master/LICENSE.TXT)
[![Python 3.7](https://img.shields.io/badge/python-3.7-blue.svg)](https://www.python.org/downloads/release/python-378/)
[![Solvve](https://img.shields.io/badge/made%20in-solvve-blue)](https://solvve.com/)

## Description

The Global Wheat Head Dataset is led by nine research institutes from seven countries: the University of Tokyo, Institut national de recherche pour l’agriculture, l’alimentation et l’environnement, Arvalis, ETHZ, University of Saskatchewan, University of Queensland, Nanjing Agricultural University, and Rothamsted Research. These institutions are joined by many in their pursuit of accurate wheat head detection, including the Global Institute for Food Security, DigitAg, Kubota, and Hiphen.

<img src='./static/images/0a029eead.jpg' style='width:25%'></img>


Example of the object detection using YOLO v5 algorithm.

We will follow next steps:

1. EDA

2. Installing YOLOv5

3. Preprocessing data for YOLOv5

4. Modeling

Dataset can be found https://www.kaggle.com/c/global-wheat-detection/data or by using kaggle api

`kaggle competitions download -c global-wheat-detection`