# Data_Augumentation_For_Medical_Images_Using_WGAN-GP

This project focuses on data augmentation for medical imaging using **Deep Convolutional Wasserstein GAN with Gradient Penalty (WGAN-GP)**. The dataset used is the **Chest X-Ray Pneumonia Dataset** sourced from [Kaggle](https://www.kaggle.com).

## Dataset Link 
[Click Here](https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia).

## Kaggle Notebook Link 
[Click Here](https://www.kaggle.com/code/shreyashacharya/data-augumentation-chest-x-ray-images-pneumonia)

## Key Features

- **Dataset**: Chest X-Ray images categorized into **Normal** and **Pneumonia** classes.
- **Model**: Deep Convolutional WGAN-GP for stable and efficient training of GANs.
- **Objective**: Augment the dataset by generating synthetic samples for both classes to address class imbalance and improve model generalization.

## Results

- Synthetic chest X-ray images generated for **Normal** and **Pneumonia** classes.
- Augmented data ready for downstream tasks like classification or training robust diagnostic models.

## Requirements

- Python 3.8+
- TensorFlow 2.x
- Additional dependencies listed in `requirements.txt`

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Data_Augmentation_For_Medical_Images_Using_WGAN-GP.git
   cd Data_Augmentation_For_Medical_Images_Using_WGAN-GP/data-augumentation-chest-x-ray-images-pneumonia.ipynb
2. Upload the file on colab/kaggle notebook and run it.
