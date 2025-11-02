# Cloud Type Classifier

This is my second project as part of learning I am doing through a course called **Practical Deep Learning for Coders** at https://course.fast.ai/. My first project is [Is_It_a_Bird](https://github.com/kristenfoshay/Is_It_a_Bird).

## Stack

- Python with Jupyter Notebook
- FastAI (computer vision library built on PyTorch)
- PIL for image processing
- DuckDuckGo Search (ddgs) for web scraping images
- ResNet34 CNN architecture for transfer learning

## What it does

Cloud type classification system that:

1. Downloads cloud images from web search for 4 types: cirrus, cumulus, stratus, nimbus
2. Creates a dataset with data augmentation and train/validation split
3. Trains a ResNet34 model using transfer learning
4. Evaluates performance with confusion matrix and top losses visualization
5. Exports trained model for inference on new cloud images# Cloud-Type-Classifier
