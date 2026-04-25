# Handwritten Digit Recognition using Neural Networks

A Deep Learning project that classifies handwritten digits (0-9) using a feedforward neural network built with TensorFlow and Keras.

##  Project Overview
I've implements a Deep Learning model to classify handwritten digits (0–9) using TensorFlow and Keras. It features a feedforward neural network with ReLU hidden layers and a Softmax output. By leveraging the Adam optimizer, the model achieves high accuracy on MNIST-style data, showcasing an end-to-end ML pipeline.


## Tech Stack
* **Language:** Python
* **Deep Learning:** TensorFlow, Keras
* **Data Analysis:** NumPy, Pandas
* **Visualization:** Matplotlib
* **Environment:** Jupyter Notebook

## Project Pipeline
* **Preprocessing:** Normalizing pixel intensity values (scaling 0–255 to 0–1) for faster model convergence.
* **Data Partitioning:** Splitting the training set into training and validation subsets to monitor performance.
* **Label Encoding:** Converting integer labels into one-hot encoded vectors for multi-class classification.
* **Model Construction:** Defining a Sequential architecture with Flatten and Dense layers.
* **Compilation:** Configuring the model with the Adam optimizer and categorical cross-entropy loss.
* **Training:** Fitting the model over multiple epochs and tracking accuracy/loss metrics.
* **Evaluation & Visualization:** Plotting training history and generating visual predictions on unseen data.

##  Model Architecture
1. **Flatten Layer:** Converts 28x28 images into a 1D vector.
2. **Dense Hidden Layer:** 128 neurons with ReLU activation.
3. **Dense Hidden Layer:** 64 neurons with ReLU activation.
4. **Output Layer:** 10 neurons with Softmax activation (one for each digit).


## How to Use
1. Clone the repository.
2. Install dependencies: `pip install tensorflow pandas numpy matplotlib`
3. Place `Train.csv` and `test.csv` in the directory.
4. Open and run `Handwritten_Digit_Recognition_using_Neural_Network.ipynb`.

---
**Author:** Anwesha Banerjee


