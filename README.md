# Multimodal Image Captioning using Deep Learning

This repository contains the full implementation of a multimodal image captioning project using the Wikipedia-based WIT English dataset. The project explores multiple deep learning architectures combining computer vision and natural language processing techniques to automatically generate descriptive captions for images.

## 📝 Project Overview

The project is divided into several phases including data preprocessing, model development, training, evaluation, and performance comparison. It investigates a variety of model architectures such as:

- CNN + LSTM (Vanilla RNN)
- CNN + GRU
- CNN + Attention + LSTM
- CNN + Transformer Decoder
- CNN + BERT Fusion with Transformer Encoder

Each model is evaluated using BLEU scores and visualized through training/validation accuracy and loss metrics.

## 📁 Project Structure

The repository is organized into clearly separated folders for data, models, evaluation, utilities, notebooks, and the final IEEE-style LaTeX report.

## 🚀 Features

- Advanced data preprocessing pipeline for both images and text
- Custom PyTorch Dataset and DataLoader for multimodal training
- Multiple model architectures with modular code
- Support for mixed precision training
- Evaluation using BLEU score and qualitative caption generation
- Comparative analysis of all models with visualizations
- Final research report in IEEE format (LaTeX)

## 📦 Setup Instructions

1. Clone the repository:
   ```
   git clone https://github.com/RudraPankaj/multimodal-wiki-captioning.git
   cd image-captioning-project
   ```
2. Install dependencies:
    ```
    pip install -r requirements.txt
    ```
3. Create and activate a conda environment:
    ```
    conda env create -f environment.yml
    conda activate captioning-env
    ```
4. Run training/evaluation scripts from the models/ directory.

## 📊 Results
The project concludes with a comparative analysis of the models based on BLEU score and training performance. The best-performing model is identified and discussed in the final report.

## 📄 Report
The detailed report is available in the report/ directory in IEEE double-column format, covering methodology, model descriptions, experiments, and findings.

## 🛡 License
This project is licensed under the MIT License - see the LICENSE file for details.

## ✨ Acknowledgements
- WIT (Wikipedia-based Image Text) Dataset
- PyTorch and HuggingFace Transformers
- Matplotlib and Seaborn for visualizations
