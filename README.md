# Deep Learning Keras Library 

# Regression-based-Problem---Kera-and-TensorFlow---US-Economies-Dataset

Regression-based neural networks - Using Kera and TensorFlow - Car Dataset
Keras is an application programming interface (API) used for running high-level neural networks. The model runs on top of TensorFlow which was developed by Google. Keras is recognized as one of the most popular deep learning libraries in Python for research and development because of it ease of use and its simplicity. However, the Scikit-learn library is the most popular library for general machine learning in Python. Most times, building a very complex deep learning network could be challenging but with Keras, this can be achieved with only a few lines of code.

I will be using Keras Library to build a regression models using the US Economic time series Data set, The dataset could be download here and saved into CSV - https://raw.githubusercontent.com/tidyverse/ggplot2/master/data-raw/economics.csv or https://github.com/tidyverse/ggplot2/blob/master/data-raw/economics.csv.

The data set contains 574 rows and 5 variables.

Date - The date the data was recorded
Psavert - Personal savings rate.
Pce - Personal consumption expenditures, in billions of dollars.
Uempmed - Median duration of unemployment, in weeks.
Pop - Total population, in thousands.
Unemploy- Number of unemployed in thousands (dependent variable).

# Deep Learning Neural Network¶
The basic architecture of the deep learning neural network, which we will be following, consists of three main components.

1) Input Layer: This is where the training observations are fed. The number of predictor variables is also specified here through the neurons.

2) Hidden Layers: These are the intermediate layers between the input and output layers. The deep neural network learns about the relationships 
   involved in data in this component.

3) Output Layer: This is the layer where the final output is extracted from what’s happening in the previous two layers. In case of regression problems, 
   the output later will have one neuron.

# Problem Statement¶
Across the Nations of the world, unemployment has become a major socio-economic and political problem. However, each government has a specific way of managing this 
very task, while managing unemployment within an economy, it is very important to predict it as well. I will be building a deep learning regression model using Keras 
to predict unemployment.

# Model Evaluation Metric
The performance of the model using Root Mean Squared Error (RMSE) which is commonly used metric when evaluating problems. RMSE measures the average magnitude of the 
residuals or error. Mathematically, it is computed as the square root of the average of square differences between predicted and actual values.
