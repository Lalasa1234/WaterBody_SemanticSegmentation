## What is this about ⁉️
**Semantic segmentation of water bodies from satellite imagery**

This has a practical application in the space industry which researches extensively on planetary water bodies.

### What is the model architecture❔
Involves building the U-Net model architecture from the scratch. U-Net assigns class to every pixel (water as the foreground versus non-water as the background)
![image](https://github.com/user-attachments/assets/c9336bb4-71f8-4df3-ae85-b6c5698b6d16)


Reference: https://arxiv.org/abs/1505.04597

### Coding Blocks 👩‍💻👩‍💻 

*EDA and testing geometric, color-space, and miscellaneous transformations*

*Defining the PyTorch Dataset and Dataloader functions along with specific transformations for image data and masked data*

*Defining the encoder/upsampling, bottleneck and decoder/downsampling block along with skip connections from encoder to its corresponding decoder*

*Training and evaluating the Model for 10 epochs along with tqdm tracking of loss*

**Note:** *Specials comments for common mistake handling and justification throughout the code*

### Results 📊📈

**Interpretation**

With just 2 epochs, the model is able to able to segment with at least 50% of accuracy. With more computational resources and training, the model is expected to predict better.


<img width="414" alt="image" src="https://github.com/user-attachments/assets/1106bf3d-ac6f-449b-aebf-2d51480fcc10">
___

<img width="412" alt="image" src="https://github.com/user-attachments/assets/a946c3f1-a05d-4251-b046-03df177813f3">


