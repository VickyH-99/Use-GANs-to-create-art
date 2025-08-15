# Use-GANs-to-create-art
## Project Overview

This project implements a **CycleGAN-based image-to-image translation model** to transform real-world photographs into **Monet-style paintings** using the **Kaggle GAN Getting Started (Monet Painting Dataset)**. The dataset contains Monet paintings and real photos in both JPG and TFRecord formats.

The workflow includes:
1. **Exploratory Data Analysis (EDA)** – inspecting dataset composition, image dimensions, and visual samples.
2. **Model Design & Training** – building a ResNet-based generator and PatchGAN discriminator with adversarial, cycle-consistency, and identity losses.
3. **Evaluation & Submission** – generating Monet-style images from real photos, submitting results to Kaggle for **MiFID** scoring, and recording leaderboard position.

This project fulfills Coursera Week 5 GAN mini-project requirements by delivering:
- A Jupyter Notebook with problem description, methodology, results, and discussion.
- A public GitHub repository containing source code and notebooks.
- A screenshot of the Kaggle competition leaderboard showing the model’s performance.
