# 👤 Human Face Generator (GAN Project)

## 📌 Overview
This project focuses on building a **Generative Adversarial Network (GAN)** to generate realistic human faces.  
Using the **Flickr-Faces-HQ Dataset (FFHQ)**, the model learns to distinguish between real and fake images while generating synthetic human face images at **64×64 resolution**.

The implementation is done in **PyTorch** with custom CNN-based Generator and Discriminator models.

---

## 📂 Dataset
- **Name:** [Flickr-Faces-HQ Dataset (FFHQ)](https://www.kaggle.com/datasets/arnaud58/flickrfaceshq-dataset-ffhq)  
- **Description:** A large-scale dataset of human faces with diverse attributes.  
- **Size:** 70,000 high-quality images.  
- **Usage:** Used ImageFolder module in PyTorch to load images and applied transformations for training.  

---

## ⚙️ Methodology
1. **Data Loading & Preprocessing**
   - Used `ImageFolder` to access the dataset.  
   - Applied PyTorch transformations (resizing, normalization, augmentation).  
   - Constructed a training set for GAN.  

2. **Model Architecture**
   - **Generator (CNN-based):** Produces synthetic 64×64 face images.  
   - **Discriminator (CNN-based):** Classifies real vs fake images.  

3. **Training**
   - Built a GAN framework in PyTorch.  
   - Trained with the FFHQ dataset.  
   - Generated **52,000 synthetic images** of human faces.  

---

## 🚀 Results
- Generated human face images at **64×64 resolution**.  
- Discriminator successfully learned to differentiate real vs fake.  
- The GAN produced thousands of realistic human-like faces.  

---

## ⚙️ Installation
Clone the repository and install dependencies:

```bash
git clone https://github.com/mehra01/human-face-generator.git
cd human-face-generator
pip install -r requirements.txt
