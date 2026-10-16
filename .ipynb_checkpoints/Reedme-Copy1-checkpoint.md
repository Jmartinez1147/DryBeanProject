Basic Neural Network Demo
Dataset
Iris Dataset

150 flower samples.

Features:

sepal_length_cm
sepal_width_cm
petal_length_cm
petal_width_cm
Target:

species
Models
Dummy Classifier (Baseline)
Neural Network (4 Neurons)
Neural Network (8 Neurons)
Results
Baseline Accuracy: approximately 0.33

Final Test Accuracy: 0.9333

New Flower Prediction: setosa

Summary
A neural network was trained to classify iris flowers using four measurements.

The final model was chosen using validation accuracy and then evaluated on an untouched test set.

The final model achieved approximately 93.3% accuracy on the reserved test set.

Setup
Install requirements:

pip install -r requirements.txt