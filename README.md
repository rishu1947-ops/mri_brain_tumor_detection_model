# mri_brain_tumor_detection_model


This project implements a Convolutional Neural Network (CNN) using PyTorch to classify Brain MRI images as either containing a tumor ('yes') or not containing a tumor ('no').

The dataset used is publicly available on Kaggle: [Brain MRI Images for Brain Tumor Detection](https://www.kaggle.com/datasets/navoneel/brain-mri-images-for-brain-tumor-detection).

## Features

-   Downloads the dataset automatically using `kagglehub`.
-   Processes and flattens image pixel data into a CSV format.
-   Utilizes a custom PyTorch `Dataset` and `DataLoader` for efficient data handling.
-   Implements a simple CNN model architecture.
-   Includes data splitting, scaling, and basic training loop setup.

## Setup

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/rishu1947-ops/mri_brain_tumor_detection_model
    cd brain-mri-detection
    ```

2.  **Install dependencies:**
    It's recommended to use a virtual environment.
    ```bash
    pip install -r requirements.txt
    ```
    *Note: Ensure you have the correct PyTorch version installed, potentially with CUDA support if you have a compatible GPU. Refer to the [PyTorch website](https://pytorch.org/get-started/locally/) for detailed installation instructions.*

3.  **Kaggle API (Optional but Recommended):**
    `kagglehub` downloads the dataset automatically. If you encounter issues or want more control, you might need to set up your Kaggle API credentials. See the `kagglehub` documentation for details.
