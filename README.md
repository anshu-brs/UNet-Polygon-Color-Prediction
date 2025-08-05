# Ayna ML Assignment: UNet Polygon Color Prediction

This repository contains a UNet model implementation for predicting colored polygon images, developed as part of the Ayna ML assignment. The project uses Google Colab for training and inference, with Weights & Biases (wandb) for tracking.

## Project Structure
- `mlassignment.py`: Python script for training the UNet model (in "MLAssignment" Colab).
- `validation.py`: Python script for inference and testing with user input (in "Validation" Colab).
- `best_unet_model.pth`: Trained model weights.
- `insights_report.md`: Analysis of model performance.
- `README.md`: This file.

## Installation
1. Clone the repository: `git clone https://github.com/anshu-brs/ayna_ml_project.git`
2. Install dependencies: `pip install torch torchvision pillow numpy matplotlib wandb`
3. Download `best_unet_model.pth` and place it in the root directory.

## Usage
- **Training**: Run `mlassignment.py` in the "MLAssignment" Colab to train the model (requires `dataset (6).zip`).
- **Inference**: Run `validation.py` in the "Validation" Colab to test the model.
  - Enter a shape (e.g., `star.png`) and color (e.g., `yellow`) when prompted.
  - View predicted and ground truth images (if available).

## Tracking
- wandb Project: [https://wandb.ai/anshu-namana-mahindra-university/ayna_ml_assignment](https://wandb.ai/anshu-namana-mahindra-university/ayna_ml_assignment)

## Acknowledgments
- xAI and Ayna ML for the assignment framework.
- wandb for experiment tracking.
