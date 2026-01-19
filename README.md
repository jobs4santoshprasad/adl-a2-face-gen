# Face Modification and Generation using VAE, β-VAE, VQ-VAE, and GAN

This repository contains the implementation for **Assignment 2** of the
**Advanced Deep Learning (ADL)** course.

The project explores and compares multiple generative models for face image
reconstruction, modification, and synthesis using the CelebA dataset.

---

##  Project Structure

```
├── adl_a2_face_gen.ipynb
├── requirements.txt
└── README.md
```


---

##  Models Implemented

- Variational Autoencoder (VAE)
- β-Variational Autoencoder (β-VAE)
- Vector Quantized VAE (VQ-VAE) with PixelCNN prior
- Generative Adversarial Network (GAN)

---

##  Dependencies

All required Python packages are listed in `requirements.txt`.

### requirements.txt

- numpy
- pandas
- matplotlib
- torch
- torchvision
- tqdm
- ipykernel


---

##  Environment Setup (One-Time)

It is recommended to use a Python virtual environment.

### Step 1: Create Virtual Environment

```bash
python -m venv adl-a2-face-gen

```
### Step 2: Activate Virtual Environment (Linux)

```
source ./bin/activate

```
### On Windows (PowerShell)

```
adl-a2-face-gen\Scripts\Activate.ps1

```
### Step 3: Install Dependencies

```

pip install -r requirements.txt

```

### Step 4: Register Jupyter Kernel

```
pip install ipykernel

python -m ipykernel install --user --name adl-a2-face-gen --display-name "Python (ADL)"

```