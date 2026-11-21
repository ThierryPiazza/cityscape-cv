# Cityscape segmentation

Project for the *Computer Vision and Deep Learning* course.

## Authors
- Grasso Gianni
- Gusmini Massimiliano
- Piazza Thierry

## Dataset

Urban street scene images with dense semantic segmentation masks, derived from Cityscapes (Cordts et al., CVPR 2016).

- **Source**: [Cityscape Dataset: Urban Street Scene Segmentation — Kaggle](https://www.kaggle.com/datasets/electraawais/cityscape-dataset)

The dataset is not included in the repository: download it from the link above and unzip it into `dataset/`.

## Setup
```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
jupyter notebook main.ipynb
```