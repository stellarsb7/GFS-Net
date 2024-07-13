# GFS-Net
This repository contains the code and results of the GFS-Net Model, a metaheuristic optimization based Deep Feature Selection for Oral Cancer Classification.

#### [Saptarshi Bandyopadhyay](https://www.linkedin.com/in/spiralsb3/)\*, [Sugata Laha](https://www.linkedin.com/in/sugata-laha-0830871b1/)\*, [Akash Halder](https://www.linkedin.com/in/akash-halder-1b315b1b7/)\* and [Ram Sarkar](https://jadavpuruniversity.in/faculty-profile/ram-sarkar/)\*
\* Equally contributing first authors

Submitted to ANNPR, 2024

## Datasets
#### [Histopathologic oral cancer identification dataset.](https://www.kaggle.com/datasets/ashenafifasilkebede/dataset)
#### [Shivam Barot. Oral cancer (lips and tongue) dataset.](https://www.kaggle.com/datasets/shivam17299/oral-cancer-lips-and-tongue-images)

## Abstract
Oral cancer is a serious hazard to world health, with many new cases recorded each year. Researchers have been concentrating on developing medical image analysis-based computer-aided diagnostic (CAD) systems for oral cancer. To this end, we propose a novel model that we name Gray Wolf Optimization (GWO) based deep Feature Selection Network (GFS-Net). Initially, we use an attention-aided NASNet Mobile, a convolutional neural network (CNN) architecture, to extract features from the input images. Next, we use the well-known metaheuristic-based optimization algorithm GWO to get rid of the extraneous features obtained from the CNN model. For the final classification task, the K-Nearest-Neighbours (KNN) classifier is applied with this optimal feature set. Our model is evaluated on two publicly accessible oral cancer datasets, histopathologic oral cancer identification dataset and oral cancer (lips and tongue) dataset, that yields classification accuracies of 92.86\% and 93.94\%, respectively.

## Contribution
1. We propose GFS-Net, a new model for oral cancer classification.

2. GFS-Net uses NAS-Net Mobile architecture combined with a squeeze and excite attention module, to extract features from the images.

3. The unimportant features generated from the CNN model have been excluded using a meta-heuristic algorithm called GWO.

4. The optimal feature set thus obtained is fed to the KNN classifier for classification.

5. The model achieves 92.86% and 93.94% accuracies on histopathologic oral cancer identification and oral cancer (lips and tongue) datasets, respectively.
