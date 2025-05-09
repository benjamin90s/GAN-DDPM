# GAN-DDPM
This project involves training a Generative Adversarial Network (GAN) on the CIFAR-10 dataset and a Denoising Diffusion Probabilistic Model (DDPM) on the Animal Faces (AFHQ) dataset.

Execute the cells in sequence from top to bottom by pressing Shift + Enter on each cell or by using the "Run All" feature in the Jupyter interface.
DC-GAN runtime: ~ 1 hour.
DDPM runtime: ~ 10 hours.

Directory Structure<img width="624" alt="Screenshot 2025-05-09 at 10 48 34 PM" src="https://github.com/user-attachments/assets/30491bc0-a389-413b-9325-25ca2292db09" />

GenerativeModels/
├── afhq_all/               # Preprocessed AFHQ dataset
├── data/                   # Cifar10 data resources
├── ddpm_fid_images/        # Real and generated images for FID computation (DDPM)
├── extracted_images_1000/  # Images extracted from notebook output (1000-step DDPM)
├── GAN&DDPM.ipynb  # Evaluation & experiments notebook
