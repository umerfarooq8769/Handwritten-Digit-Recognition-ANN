# 🖋️ Handwritten Digit Classification using ANN

Implementing an Artificial Neural Network (ANN) to recognize and classify handwritten digits (0-9).

# 📌 Project Abstract
This is my Level 2 Final Project. I developed a Deep Learning model using the MNIST dataset, which contains 70,000 images of handwritten digits. The goal was to build a Multi-Layer Perceptron (MLP) that can accurately identify numbers written by humans.

# 🛠️ Technology Stack
Deep Learning Framework: TensorFlow / Keras

Libraries: NumPy (Data processing), Matplotlib & Seaborn (Visualization)

Model Type: Artificial Neural Network (ANN)

# 🧠 Neural Network Architecture
The model is structured with three main layers:

Input Layer: Flattens the 28x28 pixel images into a 1D vector of 784 neurons.

Hidden Layers: Dense layers with ReLU activation functions to learn complex patterns and curves of the digits.

Output Layer: 10 neurons with Softmax activation to predict the probability for each digit (0-9).

# 📊 Evaluation & Results
I evaluated the model using a Confusion Matrix to see which digits the model sometimes confuses (e.g., 4 and 9).

Accuracy: [Insert your accuracy, e.g., 98%]

Key Metric: Used Categorical Crossentropy as the loss function for multi-class classification.

# 📝 Conclusion
This project successfully demonstrates how neural networks mimic the human brain to process visual information. It’s a solid foundation for moving towards Convolutional Neural Networks (CNN) for more complex image recognition tasks.

Developed By: Umer Farooq (AI Level 2 Final Project)
