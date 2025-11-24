# UNET-Image-Segmentation
# Study Desk Image Segmentation with Pretrained U-Net

This repository contains a Google Colab notebook that applies image segmentation on photographs of a study desk using a pretrained U-Net model. The model produces a binary mask separating foreground elements from the background. 

## Model Details

- **Model**: `unet_carvana`
- **Source**: [PyTorch Hub — milesial/Pytorch-UNet](https://pytorch.org/hub/milesial_pytorch-unet/)
- **Architecture**: U-Net (Encoder + Decoder)
- **Pretrained on**: Carvana Image Masking dataset
- **Task**: Binary segmentation (foreground/background)

## Inference Pipeline

1. **Input Image**  
   - Load and preprocess a study desk photograph.

2. **Model Forward Pass**  
   - Process the image through the U-Net encoder-decoder architecture.

3. **Output Mask**  
   - Generate a binary segmentation mask for the input image.

## Getting Started

- The main notebook demonstrates the entire pipeline from image loading to mask generation.
- For details, see the notebook file in this repository.

---

Feel free to use or adapt this repository for similar image segmentation tasks using pretrained models!
