[![HitCount](http://hits.dwyl.com/swapnanildutta/Tensorflow-Deployment.svg)](http://hits.dwyl.com/swapnanildutta/Tensorflow-Deployment)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com) 

<img src="images\5.png" width="512" height="380">

# Tensorflow-Deployment
TensorFlow models using TensorFlow Serving and Docker, a simple web application with Flask which will serve as an interface to get predictions from the served TensorFlow model.

## Frameworks:
### Flask
Flask is a micro web framework written in Python. It is classified as a microframework because it does not require particular tools or libraries. It has no database abstraction layer, form validation, or any other components where pre-existing third-party libraries provide common functions.

### Tensorflow Serving
TensorFlow Serving is a flexible, high-performance serving system for machine learning models, designed for production environments. TensorFlow Serving makes it easy to deploy new algorithms and experiments, while keeping the same server architecture and APIs. TensorFlow Serving provides out-of-the-box integration with TensorFlow models, but can be easily extended to serve other types of models and data.

## Working Diagram:
<img src="images\2.png" width="560" height="390">

## Required Setup:
- Python3 with Tensorflow, Flask, and Flask Bootstrap
- Docker with Tensorflow Serving

## Output:

### Trying with a cat's image
![Cat Prediction](images\cat.gif)

### Also trying with a dog's image
![Dog Prediction](images\dog.gif)