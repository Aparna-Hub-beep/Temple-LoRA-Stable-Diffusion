# Temple LoRA Training using Stable Diffusion

## Overview

This project explores fine-tuning Stable Diffusion v1.5 using LoRA (Low-Rank Adaptation) on a custom dataset of Indian temple architecture images.

The goal of the project was to understand:

* Diffusion Models
* Stable Diffusion
* Variational Autoencoders (VAEs)
* U-Net Architecture
* LoRA Fine-Tuning
* Gradient Descent
* Weights and Biases (W&B)
* Hugging Face Diffusers

## Dataset

The dataset consists of temple architecture images paired with text captions.

Example:

img000.jpg ↔ img000.txt

img001.jpg ↔ img001.txt

Each caption describes the corresponding temple image.

## Model

Base Model:

* Stable Diffusion v1.5

Fine-Tuning Method:

* LoRA (Low-Rank Adaptation)

## Training Configuration

* Resolution: 512 × 512
* Batch Size: 1
* Learning Rate: 1e-4
* Training Steps: 500
* LoRA Rank Experiments:

  * Rank 4
  * Rank 8

## Experiment Tracking

Training metrics were monitored using Weights & Biases (W&B).

Tracked metrics include:

* Training Loss
* Learning Rate
* Training Steps

## Technologies Used

* Python
* PyTorch
* Diffusers
* Transformers
* Accelerate
* PEFT
* Weights & Biases

## Future Improvements

* Train Rank 16 and Rank 32 LoRA models
* Increase dataset size
* Compare generated image quality across LoRA ranks
* Experiment with SDXL-based LoRA training

## Author

Aparna Ivaturi

B.Tech Computer Science and Engineering
