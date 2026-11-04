# Plant Disease Detection Using Deep Learning

A computer-vision project that classifies plant leaf images into disease categories using a convolutional neural network.

## Project capabilities
- Leaf-image classification across the configured classes.
- PyTorch-based deep-learning model.
- Flask web interface for image-based prediction.
- Sample images for testing, where included.

## Technology
Python · PyTorch · CNN · Flask · Jupyter Notebook

## Dataset
The existing documentation references the PlantVillage dataset. Confirm the exact dataset version, class mapping and model checkpoint used by the current code before training or inference.

## Run locally
```bash
git clone https://github.com/Ravi506051/Plant-Disease-Detection.git
cd Plant-Disease-Detection
pip install -r requirements.txt
```
If the project uses a separately distributed model checkpoint, download it from the source documented in the repository and place it at the expected path. Start the Flask app using the entry-point instructions in the project folder.

## Validation
Evaluate with a held-out dataset and report per-class precision, recall, F1-score and a confusion matrix. Test images from different lighting conditions and backgrounds to understand generalization.

## Disclaimer
This project is an educational image-classification tool. Predictions are not a substitute for expert agricultural diagnosis or local extension advice.

## Future work
Add confidence calibration, real-world field-image testing, model versioning and a clear record of dataset provenance.

## Maintainer
**Ravi Kumar Rao** · [GitHub](https://github.com/Ravi506051)

## Skills Demonstrated

- Image classification
- convolutional neural networks
- image preprocessing
- model validation
- computer-vision application development.

## Portfolio Context

This project is part of my hands-on learning portfolio. The repository documents the workflow and implementation; results should be reproduced from the included code and data before being used in reports or professional claims.
