# Hurricane-Wind-Speed-Prediction

It is a machine learning model to predict hurricane wind speeds. This model utilizes convolutional neural networks (cnn) for prediction and is written in python programming language.

## Introduction

This repository contains a machine learning model designed to predict hurricane wind speeds. The model is trained on historical hurricane data and uses advanced machine learning techniques to make accurate predictions.
The ability to predict hurricane wind speeds is crucial for disaster preparedness and response. Accurate predictions can help authorities make informed decisions about evacuations and other safety measures. They can also help residents of hurricane-prone areas prepare for storms.

## Technologies

This project is implemented in Python and uses several libraries, including:
- NumPy
- pandas
- scikit-learn
- Keras

## Installation

To install this project, follow these steps:
1. Clone the repository: `git clone https://github.com/ALAG11/Hurricane-Wind-Speed-Prediction.git`
2. Navigate to the project directory: `cd Hurricane-Wind-Speed-Prediction`
3. Install the required packages: `pip install -r requirements.txt`
4. And then first run the `DataDownload.py` file to download the historical hurricane imagery data.
5. After running the `DataDownload.py` run `DataAssembling.py` file to assemble the dataset and map the imagery dataset with the `besttrack.csv` hurricane dataset and will give you two `.npy` one for training and one for testing the model.
6. After that finally run `Model.py` file to run the mode and make predictions. In `Model.py` first that script augment the images and then do the prediciton with the help of convolutional neural network (cnn).
7. After that in your project directory you can see two images given as output by your model `Distribution of Absolute Error By Category.png` and `Median Absolute Error in Neural Network’s Predictions By Category.png` giving you the performance of the model on the testing dataset.

## Contributing

Contributions are welcome!

## License

This project is licensed under the terms of the Apache License 2.0. See the LICENSE file for details.
