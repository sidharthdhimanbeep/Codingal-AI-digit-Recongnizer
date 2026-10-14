# Codingal AI Digit Recognizer

A deep learning handwritten digit recognizer trained on the MNIST dataset using TensorFlow/Keras and data augmentation.

## Features

- **MNIST Dataset**: Automatically loads and normalizes the standard handwritten digit benchmark dataset (60,000 training images, 10,000 test images).
- **Data Augmentation**: Employs `ImageDataGenerator` for rotation, zoom, width shift, and height shift to improve generalization.
- **Deep Neural Network**: Multi-layer Dense network with `LeakyReLU` activations and `RMSprop` optimizer.
- **Visualizations**: Plots and saves training/validation accuracy, loss curves, and sample test predictions with color-coded labels (green for correct, red for incorrect).
- **Model Persistence**: Saves the trained classifier model in the modern `.keras` format (`digit_classifier.keras`).

## Setup and Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/sidharthdhimanbeep/Codingal-AI-digit-Recongnizer.git
   cd Codingal-AI-digit-Recongnizer
   ```

2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the model training and evaluation:**
   ```bash
   python main.py
   ```
