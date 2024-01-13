# GRU for Sine Wave Prediction

Description: "This project implements a Gated Recurrent Unit (GRU) model using PyTorch to predict the next value in a sine wave sequence. The model is trained on synthetic sine wave data and evaluated by comparing its predictions to the true values."

Features:
  - Generates synthetic sine wave data for supervised learning tasks.
  - Implements a GRU model with:
      - 2 GRU layers with 64 hidden units.
      - A fully connected layer to map the final GRU output to the target value.
  - Trains the model using Mean Squared Error (MSE) loss and Adam optimizer.
  - Visualizes:
      - Training loss over epochs.
      - Predicted vs true values for the test dataset.
