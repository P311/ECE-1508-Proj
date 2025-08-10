# Data For ECE1508 Project: Text-to-Image Generation using Pretrained LMs and Generative Architectures

Each csv file has two main differences:
1. Number of captions: Generated from first 10000 image-label pairs or the full dataset (50000 pairs).
2. Random / CLip: As we discussed in the report, we find 3 dominant colors using K-Means algorithm. After that there are two approaches to get the top one dominant color
    1. Random: randomly choose one from dominant colors
    2. Clip: Using clip model to find out which color best describes the image, and choose that one.

For outputs folder, it includes a series of generated sample images after each epoch.

Trained GAN model is saved as discriminator.pth and generator.pth.

Our code is in notebook 1508_Proj.ipynb. We ran it in Google Colab with L4 GPU.
