# 🌿 Plant Disease Detection Using Deep Learning

An AI-powered plant leaf classification project built using a Convolutional Neural Network (CNN) and PyTorch. The project aims to identify plant diseases from leaf images and support early disease awareness.

## ✨ Features

- Classifies leaf images into 39 categories
- Deep learning model built with PyTorch
- Flask-based web application
- Sample images available for testing
- Pre-trained model support

## 🛠️ Technologies Used

- Python
- PyTorch
- Deep Learning
- Convolutional Neural Networks (CNN)
- Flask
- Jupyter Notebook

## 📊 Dataset

This project uses the PlantVillage dataset for training. Refer to the original project resources for dataset access and details.

## 🚀 Installation and Setup

1. Clone or download this repository.
2. Install the Python version and dependencies required by the project.
3. Install dependencies using `pip install -r requirements.txt` from the folder containing the requirements file.
4. Download `plant_disease_model_1.pt` from the model link provided in the original README, if needed.
5. Place the model file in the `Flask Deployed App` folder as required by the application.
6. Open a terminal in that folder and run `python app.py`.
7. Open the local URL displayed by Flask in your browser.

## 🧪 Testing

Use the sample leaf images in the `test_images` folder to test predictions. Results may vary depending on image quality and whether the input resembles the training data.

## 🔮 Future Improvements

- Add model evaluation using precision, recall, F1-score and a confusion matrix
- Improve performance on real-world images
- Add prediction confidence scores
- Improve the user interface and mobile responsiveness
- Add clearer guidance about model limitations

## ⚠️ Disclaimer

This project is for educational purposes. Model predictions are not a substitute for professional agricultural diagnosis.

## 👨‍💻 Author

Ravi Kumar Rao

GitHub: https://github.com/Ravi506051

## 🤝 Contributions

Contributions and suggestions for improving the code, documentation and user interface are welcome.

## Model Evaluation Checklist

For a meaningful evaluation, keep test images separate from training data and report per-class precision, recall, F1-score, and a confusion matrix. Test images captured outside the training dataset to understand how lighting, background, camera quality, and leaf condition affect predictions. Record the model checkpoint and preprocessing used for each evaluation.

## Responsible Use

Predictions are intended for educational demonstration and early awareness only. Confirm suspected plant diseases with a qualified agricultural expert before taking treatment or pesticide decisions.

## Project Development Notes

Evaluate per-class precision, recall, F1, and confusion matrix on images separate from training. Test varied lighting and backgrounds; predictions should be confirmed by an agricultural expert.

For reproducible updates, record the dataset or upstream version, environment and dependency versions, configuration, and actual outputs from each run. Keep illustrative examples clearly labelled and never commit credentials or private data.

### Technical Deep Dive

For image classification, apply the same resize, channel ordering, and normalization at inference that were used during training. Evaluate on images held out from training and report per-class precision, recall, F1-score, and a confusion matrix across all 39 labels. Test external photographs with different lighting, backgrounds, camera quality, and leaf orientations to understand domain shift.

Suggested engineering checks: validate image decoding and tensor shape, load checkpoints with the expected architecture, keep class-index mappings versioned with the model, and display uncertainty without presenting predictions as a definitive agricultural diagnosis.

## Model Validation and Responsible Use

- Keep test images separate from training data and evaluate per-class precision, recall, F1-score, and a confusion matrix.
- Test on real-world images with different lighting, backgrounds, camera quality, and leaf orientations.
- Record the model checkpoint, input resizing/normalization, class mapping, and dataset split for each evaluation.
- Display confidence carefully; a high model score does not guarantee a correct diagnosis.
- Use predictions for educational awareness only and seek qualified agricultural guidance before taking crop-treatment decisions.

## Computer Vision Evaluation

- Keep training, validation, and test images separated by source or plant where possible to reduce near-duplicate leakage.
- Apply image resizing and normalization consistently during training and inference.
- Report per-class precision, recall, F1-score, and a confusion matrix in addition to overall accuracy.
- Inspect false predictions across lighting, backgrounds, leaf orientation, and disease severity.
- Treat predictions as decision support only; confirm suspected plant diseases with an appropriate agricultural expert.

## Robustness and Evaluation Plan

- Keep evaluation images separate from training data and report per-class precision, recall, F1-score, and a confusion matrix.
- Test images captured under varied lighting, backgrounds, camera quality, and leaf conditions.
- Record the checkpoint, image resizing, normalization, and class mapping used for each evaluation.
- Treat predictions as preliminary educational guidance and confirm suspected disease with a qualified agricultural expert.
