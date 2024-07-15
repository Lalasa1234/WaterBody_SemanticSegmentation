## What is this about ⁉️
**Semantic segmentation of water bodies from satellite imagery**

This has a practical application in the space industry which researches extensively on planetary water bodies.

### What is the model architecture❔
Involves building the U-Net model architecture from the scratch. U-Net assigns class to every pixel (water as the foreground versus non-water as the background)
![image](https://github.com/user-attachments/assets/e72fcfd0-6ac2-4e82-bde7-5b8b89b496b5)

Reference: https://arxiv.org/abs/1505.04597

### Coding Blocks 👩‍💻👩‍💻
*EDA and testing geometric, color-space, and miscellaneous transformations *

*Defining the PyTorch Dataset and Dataloader functions along with specific transformations for image data and masked data*

*Defining the encoder/upsampling, bottleneck and decoder/downsampling block along with skip connections from encoder to its corresponding decoder*

*Training the Model for 50 epochs along with tqdm tracking of loss*

*Model Predictions*
