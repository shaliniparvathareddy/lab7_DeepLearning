# CS3807 – Deep Learning Laboratory

## Experiment 7: Autoencoders

This experiment explores different types of autoencoders using the **MNIST Handwritten Digit Dataset**.

### Models Implemented

* Fully Connected Autoencoder
* Convolutional Autoencoder (CAE)
* Denoising Autoencoder
* Variational Autoencoder (VAE)

### Dataset

**MNIST Handwritten Digits**

* Image size: `28 × 28`
* Grayscale images
* Pixel values normalized to `[0, 1]`

### Evaluation Metrics

The models are evaluated using:

* Mean Squared Error (MSE)
* Mean Absolute Error (MAE)
* Structural Similarity Index (SSIM)

### VAE Experiments

The Variational Autoencoder is used for:

* Latent-space visualization
* New image generation
* Latent-space interpolation

### Requirements

Install the required Python packages using:

```bash
pip install -r requirements.txt
```

Main dependencies:

```text
TensorFlow
NumPy
Matplotlib
scikit-image
```

### Running the Experiment

Run the provided Jupyter Notebook or Python files.

For Jupyter Notebook:

```bash
jupyter notebook
```

### Repository Structure

```text
Deep_Learning_Lab/
│
├── README.md
├── requirements.txt
├── code/
├── figures/
└── report/
```

### Results

The experiment compares the reconstruction performance of the different autoencoder models and analyzes:

* Image reconstruction
* Image denoising
* Reconstruction errors
* Latent representations
* VAE-generated images
* Latent-space interpolation

### Authors

**B.Tech Artificial Intelligence & Data Science**
**Shiv Nadar University Chennai**

**Course:** CS3807 – Deep Learning Laboratory
**Experiment:** 7

### Repository

https://github.com/atreides17122017/Deep_Learning_Lab.git
