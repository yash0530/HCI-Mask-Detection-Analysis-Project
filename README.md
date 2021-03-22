# HCI-Mask-Detection-Analysis-Project
Face Mask Detection web applicaion built with Flask, Keras-TensorFlow, OpenCV.  
It can be used to detect Face masks in real-time.  
It also provides a real-time summary of the percentage of the time mask is worn.

## HCI Project
- Veermata Jijabai Technological Institute
- Yash S. Jain (ysjain_b17@it.vjti.ac.in)
- Yash R. Jain (yrjain_b17@it.vjti.ac.in)

## Technologies
- Keras/Tensorflow
- OpenCV
- Flask
- MobilenetV2
- AJAX

## Usage
You have to install the required packages, you can do it:
- via pip
```pip install -r requirements.txt```
- or via conda
```conda env create -f environment.yml```

Once you installed all the required packages you can type in the command line from the root folder:

```
FLASK_APP=wsgi.py FLASK_ENV=development flask run
```
and click on the link that the you will see on the prompt.

## Data
The dataset used for training the model is available <a href="https://www.kaggle.com/omkargurav/face-mask-dataset">here</a>.

