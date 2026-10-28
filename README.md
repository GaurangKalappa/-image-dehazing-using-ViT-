# Image Dehazing with DehazeFormer-B

A deep learning project that uses **DehazeFormer-B** to remove haze from images. The notebook fine-tunes a pretrained model on paired hazy and clear images and evaluates the dehazing results.

## Dataset

- **Dataset:** https://www.kaggle.com/datasets/hemanthhari/dehazing-dataset-thesis

The dataset is not included in this repository. Please refer to the original Kaggle page for access and licensing information.

## Model and Weights

- **Original implementation:** https://github.com/IDKiro/DehazeFormer
- **Research paper:** https://arxiv.org/abs/2204.03883
- **Pretrained weights:** https://drive.google.com/drive/folders/1gnQiI_7Dvy-ZdQUVYXt7pW0EFQkpK39B?usp=sharing

The notebook loads the `dehazeformer-b.pth` checkpoint and fine-tunes the model on the selected dataset. Model weights are not included in this repository.

## Results

The notebook provides:
- **PSNR score** to evaluate image reconstruction quality on the test dataset.
- **Training and validation loss curves** to visualize the model's learning progress.
- **Visual comparisons** between hazy inputs, clear ground-truth images, and predicted dehazed outputs.

Numerical results and example images can be added after running the notebook and saving the outputs.

## Acknowledgements

This project builds on the original [DehazeFormer](https://github.com/IDKiro/DehazeFormer) implementation and its associated research.