# Coral_project : Harnessing Deep Learning for Timely Identification of Coral Bleaching Events in Underwater Imagery

## Overview
Coral reefs are vital marine ecosystems that support a significant portion of oceanic life and provide livelihoods for millions of people worldwide. However, rising sea temperatures driven by climate change have triggered widespread coral bleaching—a ecological crisis that threatens marine biodiversity.

Traditional tracking relies on manual imaging and classification, which is incredibly time-consuming and prone to human error. This project leverages deep learning and computer vision architectures to automate and accelerate the detection of coral bleaching events from underwater imagery. By identifying bleaching at its initial stages, marine conservationists can implement faster intervention strategies to alleviate ecosystem damage.

## Dataset Specification
The project utilizes a comprehensive, public-domain dataset containing diverse underwater images of coral reefs.
- Total Images: 923
- Class Distribution:
  - Bleached Corals: 485 images (53%)
  - Healthy Corals: 438 images (47%)
- Data Split:
  - 80% Training Dataset
  - 10% Validation Dataset
  - 10% Testing Dataset

## Notebooks
### coral-project(1)-dataset-splitting [![Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://www.kaggle.com/code/maryrobynbernabe/coral-project-1-dataset-splitting)
This notebook used the dataset from [here](https://www.kaggle.com/datasets/vencerlanz09/healthy-and-bleached-corals-image-classification) and splits it into train, validation, and test.

### coral-project(2)-mobilenetv2-training [![Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://www.kaggle.com/code/maryrobynbernabe/coral-project-2-mobilenetv2-training)
This notebook is used for training various models using MobileNetV2 model as a base model. The best model is also saved as the output of the notebook.

### coral-project(3)-testing-mobilenetv2 [![Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://www.kaggle.com/code/maryrobynbernabe/coral-project-3-mobilenetv2-testing)
This notebook is used for testing the best model acheived out of MobileNetV2 experiments.

### coral-project(4)-resnet50-training [![Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://www.kaggle.com/code/maryrobynbernabe/coral-project-4-resnet50-training)
This notebook is used for training various models using ResNet50 model as a base model. The best model is also saved as the output of the notebook.

### coral-project(5)-resnet50-testing [![Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://www.kaggle.com/code/maryrobynbernabe/coral-project-5-resnet50-testing)
This notebook is used for testing the best model acheived out of ResNet50 experiments.

### coral-project(6)-vgg16-training [![Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://www.kaggle.com/code/maryrobynbernabe/coral-project-6-vgg16-training)
This notebook is used for training various models using VGG16 model as a base model. The best model is also saved as the output of the notebook.

### coral-project(7)-vgg16-testing [![Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://www.kaggle.com/code/maryrobynbernabe/coral-project-7-vgg16-testing)
This notebook is used for testing the best model acheived out of VGG16 experiments.

### [app.py](https://github.com/bernaberobyn/coral_project/blob/main/app.py)
This is the code for streamlit dashboard deployed in streamlit cloud and can be accessed from [here](https://healthyandbleachedcorals.streamlit.app/)
