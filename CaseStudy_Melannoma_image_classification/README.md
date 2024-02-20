# Case Study: Melanoma image classification

- This is a case study of a CNN model for classifying melanoma images. The model is trained on the [ISIC 2019](https://challenge2019.isic-archive.com/) dataset. The dataset contains 25,331 images of skin lesions, including 8,431 malignant melanoma images and 15,900 benign images. The model is trained to classify the images into two classes: benign and malignant.
- We use the general CNN architecture: `VGG16`, `Inception V3`, `Resnet 50/152`, `EfficientNet B7` for this problem. Through careful optimization, we attained a best-case performance of 89%. The model is evaluated using the confusion matrix, precision, recall, and F1 score.
