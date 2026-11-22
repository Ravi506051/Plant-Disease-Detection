# Plant Disease Detection

A deep-learning project with a model-development notebook and a Flask application for classifying leaf images into the configured disease classes.

## Project areas

- Model/Plant Disease Detection Code.ipynb — notebook model workflow.
- Flask Deployed App/ — Flask app, CNN inference code, templates, static assets, and disease/supplement information CSVs.
- test_images/ and demo_images/ — example images in the repository.

## Run the Flask application

~~~bash
git clone https://github.com/Ravi506051/Plant-Disease-Detection.git
cd Plant-Disease-Detection/Flask-Deployed-App
pip install -r requirements.txt
python app.py
~~~

If your shell treats the folder name with spaces as required, use its exact repository path. Open the local address printed by Flask and try one of the sample images.

## Model notes

Predictions depend on the trained model, class mapping, preprocessing, image quality, lighting, and background. Verify the expected model files and labels in the app configuration. This educational prototype is not a substitute for confirmation from an agricultural expert.

## Maintainer

Ravi Kumar Rao · [GitHub](https://github.com/Ravi506051)
