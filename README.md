# Linear Latent Space Traversal in GANs

This repository contains a Jupyter notebook demonstrating linear latent space traversal in Generative Adversarial Networks (GANs).

## Overview

The `Linear latent space traversal.ipynb` notebook provides an implementation and visualization of linear interpolation between two points in the latent space of a GAN. This technique allows for the exploration of the generator's latent space and the observation of smooth transitions between generated images.

## Features

- Implementation of linear latent space traversal function
- Visualization of generated images along the traversal path
- Customizable number of samples and latent space dimension

## Requirements

- Python 3.x
- PyTorch
- Matplotlib
- Jupyter Notebook

## Usage

1. Open the `Linear latent space traversal.ipynb` notebook in Jupyter.
2. Ensure you have a trained GAN generator model available.
3. Run the cells in order to perform the latent space traversal and visualize the results.

## Key Components

1. `linear_latent_space_traversal` function: Performs the actual traversal between two latent vectors.
2. Dummy data generation: Creates random start and end vectors for testing.
3. Visualization: Displays the generated images along the traversal path.

## Customization

You can adjust the following parameters:
- `latent_dim`: The dimension of the latent space (should match your generator's input size).
- `num_samples`: The number of interpolation steps between the start and end vectors.

## Notes

- Ensure your generator model is properly loaded and moved to the correct device (CPU/GPU) before running the traversal.
- The code assumes a specific format for the generator's output. Adjust as necessary for your model.

## Contributing

Feel free to fork this repository and submit pull requests with improvements or additional features related to latent space exploration in GANs.
