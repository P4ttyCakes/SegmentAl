# SegmentAl

This python script utilizes the pre-trained DeepLabV3 Segmentation Model with a ResNet-50 CNN to create image masking.

Firstly, the project pre-processes an image by converting to rgb, adding padding, and normalizes using ImageNet mean and standard deviation.
The Model then applies segmentation utilizing the DeepLabV3 model to create a segmentation mask, before overlaying it upon the original image,


```bash
pip install torch torchvision numpy matplotlib pillow
```

## Usage
change file path to specified image for masking.
```Python
image_path = "/Users/patricklu/Desktop/TestImage.png"
```

##
[MIT](https://choosealicense.com/licenses/mit/)