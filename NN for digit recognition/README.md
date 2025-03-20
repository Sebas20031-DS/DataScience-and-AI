# Digit Recognition using Tensorflow

## Repository Contents

Creating a model to recognize handwritten digits is an engaging machine learning project. In this repository, I have built and compared three different models using TensorFlow to tackle this task.

## Model Selection
Navigate to the `Model_selection.ipynb` file to explore the code for comparing the three neural networks with distinct architectures. Evaluate each model using a cross-validation set and a test set. The code comments can guide you through the process. By running this code, you can generate the `M1_digit_rec.keras`, `M2_digit_rec.keras` files or create your own models.

## Model Usage
In the `Model_usage.ipynb` file, you can test the model. Remember to update the `model_path` variable with the directory where you have stored `M1_digit_rec.keras` or your custom model. In the `Digit example` folder, I have included some samples for quick verification. However, feel free to test it with your own handwritten digit image samples. Just ensure to follow the comments and markdown notes in code.

## Another Files

- `Digit example/`: Folder containing some handwritten digits to test the models with real images.
- `README.md`: This file, which describes the project.
- `requirements.txt`: List of libraries required to run the code if you use a virtual environment.
- `M1_digit_rec.keras`, `M2_digit_rec.keras`: Saved models.