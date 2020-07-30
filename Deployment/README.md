# Deploy Keras Model with Flask as Web App in 10 Minutes

[![](https://img.shields.io/badge/python%203.5%2B-green.svg)]()

> A pretty and customizable web app to deploy your DL model with ease

------------------

## Getting started in 10 minutes

- Clone this repo 
- Install requirements
- Run the script
- Check http://localhost:5002
- Done! :tada:

:point_down:Screenshot:


## Local Installation

### Clone the repo
```shell
$ git@github.com:nirmal10110/Chest-Xray-Recognition.git
```

### Install requirements

```shell
$ pip install -r requirements.txt
```

Make sure you have the following installed:
- tensorflow
- keras
- flask
- pillow
- h5py
- gevent

### Run with Python

Python 3.5+ are supported and tested.

```shell
$ python app.py
```

## Customization

### Use your own model

Place your trained `.h5` file saved by `model.save()` under models directory.




### Use other pre-trained model

See [Keras applications](https://keras.io/applications/) for more available models such as DenseNet, MobilNet, NASNet, etc.

### UI Modification

Modify files in `templates` and `static` directory.

`index.html` for the UI and `main.js` for all the behaviors

## Deployment

To deploy it for public use, you need to have a public **linux server**.

### Run the app

Run the script and hide it in background with `tmux` or `screen`.
```
$ python app.py
```
```


## More resources

[Building a simple Keras + deep learning REST API](https://blog.keras.io/building-a-simple-keras-deep-learning-rest-api.html)
