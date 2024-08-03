## What is this about ⁉️
**Semantic segmentation of water bodies from satellite imagery**

This has a practical application in the space industry, which researches extensively on planetary water bodies. The output masks can be used to detect and measure water bodies in extraterrestrial landforms.

### Which model architecture is used and why❔

**U-Net is preferred over other Fully Convolution Neural Networks like ResNet-18**

*U-Net leverages the concept of skip-connections which synergizes the low-level information (edges,color differences) from encoder with high-level information (semantics) from its corresponding decoder; making it perfect for semantic image segmentation. Skip-connections are absent in ResNet-18*

Here, the U-Net model is built from the scratch. U-Net assigns class to every pixel (water as the foreground versus non-water as the background)
![image](https://github.com/user-attachments/assets/c9336bb4-71f8-4df3-ae85-b6c5698b6d16)


Reference: https://arxiv.org/abs/1505.04597

### Coding Blocks 👩‍💻👩‍💻 

*EDA and testing geometric, color-space, and miscellaneous transformations*

*Defining the PyTorch Dataset and Dataloader functions along with specific transformations for image data and masked data*

*Defining the encoder/upsampling, bottleneck and decoder/downsampling block along with skip connections from encoder to its corresponding decoder*

*Training and evaluating the Model for 50 epochs along with tqdm tracking of loss*

**Note:** *Specials comments for common mistake handling and justification throughout the code*

### Results 📊📈

<img width="600" alt="image" src="https://github.com/user-attachments/assets/723e167b-9b75-44d6-b88c-1d5c615daa08">

____

<img width="600" alt="image" src="https://github.com/user-attachments/assets/0616c6d8-2bc9-4445-9e25-6bcd38cd2358">






