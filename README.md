# Traffic Forecasting using Spatio-Temporal Graph Neural Networks

# Project Overview
This project focuses on predicting traffic flow in the Los Angeles metropolitan area using Spatio-Temporal Graph Neural Networks. By analyzing data from sensor segments within the city, we aim to develop models that forecast traffic conditions, aiding in efficient city planning and congestion mitigation.

# Features
Implementation of Encoder-Decoder Diffusion Convolutional Recurrent Neural Network (DCRNN) and Temporal Neural Network using PyTorch for traffic prediction.
Use of ensemble learning techniques combining multiple graph-level prediction methods.
Evaluation of the proposed model on the METR-LA dataset, reflecting traffic flow across various Los Angeles regions.

# Dataset
METR-LA: Traffic speed readings from 207 sensors, spanning from March to June 2012.

Additional datasets include sensor locations and distances, enhancing the spatial analysis capability of our models.

# Technologies Used

Python, PyTorch, TensorFlow for model development.

Pandas, NumPy for data manipulation.

Matplotlib, Seaborn for data visualization.

# Getting Started

Clone the repository and navigate to the project directory.

Install required Python libraries: pip install -r requirements.txt.

Download the METR-LA dataset and additional spatial datasets, placing them in the data/ directory.

Run the preprocessing script: python preprocess.py to prepare the data for modeling.

To train the models, execute: python train.py.

For predictions, use: python predict.py --input "path/to/test/data".

# Model Evaluation
Models are evaluated using metrics such as MAE, RMSE, and MAPE. The DCRNN model demonstrated superior performance, highlighting the effectiveness of graph neural networks in capturing complex spatio-temporal relationships.

# Future Work

Expansion of the model to cover additional metropolitan areas.

Exploration of more advanced neural network architectures to enhance prediction accuracy.

# Contact Information
For further information or queries, please reach out to:

Rithwik Maramraju: rithwik.maramraju@sjsu.edu
