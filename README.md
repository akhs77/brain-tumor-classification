# Brain Tumor Detection Using VGG16

This project implements a deep learning model to classify MRI images of the brain as either containing a tumor or not. Using transfer learning with the VGG16 architecture, this model achieves accurate classification with a minimal training dataset.

## Project Structure

- `brain-mri-images-for-brain-tumor-detection.zip`: The dataset containing MRI images categorized into "yes" (tumor) and "no" (no tumor).
- `main.py`: The main script for training and evaluating the model.
- `README.md`: Project documentation.

## Dataset

The dataset used here is the "Brain MRI Images for Brain Tumor Detection" dataset, available on Kaggle. It contains MRI images labeled as:
- `yes`: Images with a brain tumor.
- `no`: Images without a brain tumor.

## Requirements

To run this project, you will need:

- Python 3.x
- Jupyter Notebook or Google Colab
- Required libraries:
  - `tensorflow`
  - `keras`
  - `opencv-python`
  - `numpy`
  - `scikit-learn`
  - `matplotlib`
  - `tqdm`
  - `kaggle` (for downloading datasets from Kaggle)

Install dependencies using:
```bash
pip install tensorflow keras opencv-python-headless numpy scikit-learn matplotlib tqdm kaggle
