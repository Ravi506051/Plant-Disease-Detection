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
