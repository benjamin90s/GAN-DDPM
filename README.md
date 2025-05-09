# GAN-DDPM
# This project involves training a Generative Adversarial Network (GAN) on the CIFAR-10 dataset and a Denoising Diffusion Probabilistic Model (DDPM) on the Animal Faces (AFHQ) dataset.

# Execute the cells in sequence from top to bottom by pressing Shift + Enter on each cell or by using the "Run All" feature in the Jupyter interface.
# DC-GAN runtime: ~ 1 hour.
# DDPM runtime: ~ 10 hours.

# Directory Structure
# Dlcv_assignment/
├── afhq_all/               # Preprocessed AFHQ dataset
├── data/                   # Cifar10 data resources
├── ddpm_fid_images/        # Real and generated images for FID computation (DDPM)
├── extracted_images_1000/  # Images extracted from notebook output (1000-step DDPM)
├── GAN&DDPM.ipynb  # Evaluation & experiments notebook
