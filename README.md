<h1>Airline Passengers Prediction using Recurrent Neural Networks (RNN)</h1>
This project aims to develop a Recurrent Neural Network (RNN) model to predict future airline passenger numbers using international airline passenger data. In this project, an RNN model has been built and trained using TensorFlow and Keras libraries.

<h2>Project Objectives</h2>
<ul>
  <li>Understanding the dataset and performing preprocessing steps</li>
  <li>Building and training the RNN model</li>
  <li>Evaluating the training and validation performance of the model</li>
  <li>Comparing predictions with actual data and visualizing results</li>
</ul>

<h2>Technologies Used</h2>
<ul>
  <li>Python</li>
  <li>TensorFlow</li>
  <li>Keras</li>
  <li>Pandas</li>
  <li>NumPy</li>
  <li>Matplotlib</li>
  <li>Scikit-learn</li>
</ul>

<h2>Usage</h2>

Clone or download the project files.

Place the international-airline-passengers.csv file in the project folder.

Install the required libraries using Anaconda or a virtual environment.

Open the airline_passengers_prediction.ipynb file in a Jupyter Notebook environment.

Run the notebook step by step to build, train, and evaluate the model.

<h2>Dataset</h2>

international-airline-passengers.csv: Contains data on international airline passenger numbers from 1949 to 1960.

Dataset link : https://www.kaggle.com/datasets/andreazzini/international-airline-passengers

<h2>Model</h2>

The model consists of a SimpleRNN layer followed by a fully connected (Dense) layer.

The model can save the weights that achieve the best performance during training.

Adam optimizer is used to optimize the model.

<h2>Results</h2>

Root Mean Squared Error (RMSE) values are calculated on both training and test data.

Actual and predicted data are visualized using graphs.

<h2>License</h2>

This project is licensed under the MIT License. For more information, see the LICENSE file.

