# SegmentAl

Built upon the Pytorch Framework, the Python script utilizes a pre-trained DeepLabV3 Segmentation Model with a ResNet-50 Backbone to classify pixel-wise labels and generate segmentation masking.

Firstly, the project utilizes PIL to load an image, Torchvision to apply padding and transformations, and normalization through ImageNet mean and Standard Deviation,

The Model then utilizes the DeepLabV3 model to create and overlay a segmentation mask upon the original image, displaying the color map and original with Matplotlib.


```bash
pip install torch torchvision numpy matplotlib pillow
```

## Usage
change file path to specified image for masking.
```Python
image_path = "/Users/patricklu/Desktop/TestImage.png"
```

![image](https://github.com/user-attachments/assets/ef36a49a-f547-4647-b45d-e61ff7ea630c)


## License 
[MIT](https://choosealicense.com/licenses/mit/)
