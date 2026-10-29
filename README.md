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

Here are a few results:

<img width="800" alt="sample1" src="https://github.com/user-attachments/assets/e806bcd3-9f9f-410a-8a43-e45b51ceddc2" />
<img width="800" alt="sample0" src="https://github.com/user-attachments/assets/282761d9-82ff-4ed3-955d-9dc01b6b5ef2" />
<img width="800" alt="sample3" src="https://github.com/user-attachments/assets/968d48f8-fc90-4f57-b5be-671f5ec5d7ce" />


## Acknowledgements

This project builds on the original [DehazeFormer](https://github.com/IDKiro/DehazeFormer) implementation and its associated research.
