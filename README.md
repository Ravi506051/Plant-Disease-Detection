# Plant Disease Detection Using Deep Learning

A computer-vision project that classifies plant leaf images into disease categories using a convolutional neural network.

## Project Capabilities
- Leaf-image classification across the classes configured in the project.
- Deep-learning inference with the model and framework included in the repository.
- Flask-based interface for image submission and prediction.
- Image preprocessing and prediction display.

## Technology
Python · PyTorch · CNN · Flask · Jupyter Notebook

## Workflow
1. Load and preprocess a leaf image.
2. Resize and normalize it to match the model's expected input.
3. Run inference with the trained CNN.
4. Map the predicted class index to its configured disease label.
5. Display the prediction in the application.

## Setup
```bash
git clone https://github.com/Ravi506051/Plant-Disease-Detection.git
cd Plant-Disease-Detection
pip install -r requirements.txt
```
Start the Flask application using the entry point provided in the repository. If a model checkpoint is distributed separately, place it at the path expected by the code.

## Evaluation and Limitations
Evaluate on a held-out dataset and report per-class precision, recall, F1-score, and a confusion matrix. Results may vary with lighting, background, camera quality, and leaf condition. This educational project is not a substitute for expert agricultural diagnosis.

## Future Improvements
- Test with real-world field images.
- Add confidence calibration and uncertainty reporting.
- Track dataset provenance and model versions.
- Add automated tests for preprocessing and prediction.

## Maintainer
**Ravi Kumar Rao** · [GitHub](https://github.com/Ravi506051)

## Model Reliability Checklist

For a reproducible experiment, keep the image preprocessing steps, class-to-index mapping, model checkpoint, and dependency versions aligned. When reporting performance, include the held-out split strategy, per-class precision/recall/F1, and a confusion matrix rather than a single accuracy number. Test images captured under different lighting and backgrounds to understand how well the model generalizes beyond curated samples.

## Example Use Case

The application can support an initial screening workflow by highlighting a possible leaf-disease class from an uploaded image. Confirm any suspected disease with an agricultural expert before taking treatment decisions.
