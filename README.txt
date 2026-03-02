
# README Project 1 Anne Utegen U91687641

------------------------------------------------------------

## 1. Project Overview

Project Title: CNN-Based Single-Image Dehazing Leveraging FFA-Net (2020)

Model Type: Resnet

Objective: Reconstruction

Dataset Used:
Name: RESIDE-6K
Link: https://www.kaggle.com/datasets/kmljts/reside-6k

Expected test evaluation for sanity check: PSNR=18-24dB, SSIM=0.70-0.85

------------------------------------------------------------

## 2. Repository Structure

Deep_Learning_Project1_Baseline/
  data/
    RESIDE-6K
      test/
        GT/
        hazy/
      train/
        GT/
        hazy/
  models/
    Resnet12_64_L1_Final.pth
  DeepLearning_Anne_Projet1.ipynb
  README.md
  requirements.txt

------------------------------------------------------------

## 3. Dataset (Choose ONE of the 3 options)

### OPTION B — CUSTOM SPLITS (test split uploaded to Box)
Box Link to Dataset:
https://usf.box.com/s/2j3es3dwq133myu27i1gqt3puffuiqyh

------------------------------------------------------------

## 4. Model Checkpoint

Box Link to Best Model Checkpoint:
https://usf.box.com/s/3ts473tmodohsjmmo4tl4n96a1jstdtx

------------------------------------------------------------

## 5. Requirements (Dependencies)

Python Version: 3.10

Dependencies: requirements.txt

Using pip:
pip install -r requirements.txt

Using conda (creates env and installs):
conda create -n dlproj python=3.10
conda activate dlproj
pip install -r requirements.txt

------------------------------------------------------------

## 6. Running the Test Script

Open DeepLearning_Anne_Projet1.ipynb in Google Colab.
Run all cells. Data preprocessing, training, and evaluation are all included inside the notebook.

------------------------------------------------------------

## 7. Running the Training Script

Open DeepLearning_Anne_Projet1.ipynb in Google Colab.
Run all cells. Data preprocessing, training, and evaluation are all included inside the notebook.

------------------------------------------------------------

## 8. Submission Checklist

- [+] Dataset provided using Option A, B, or C and placed correctly.
- [+] Model checkpoint linked and instructions for placement included.
- [+] `requirements.txt` generated and Python version specified.
- [+] Test command works.
- [+] Train command works.

------------------------------------------------------------
