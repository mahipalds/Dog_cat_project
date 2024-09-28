# Dog_cat_project

Dog vs Cat Image Classification:- This project uses Convolutional Neural Networks (CNNs) to classify images of dogs and cats. The model pipeline includes data augmentation techniques to improve generalization and transfer learning using a pre-trained model for faster and more accurate classification.

Project Overview: - The goal of this project is to build a robust image classifier that distinguishes between dog and cat images. The steps include:

CNN Architecture: A custom CNN model is initially built.

Data Augmentation: Applied to increase the diversity of the training data through transformations like rotation, flipping, and zooming.

Transfer Learning: A pre-trained model (VGG16) is fine-tuned to improve performance.

Dataset

500 images of dogs and 500 images of cats, resized to 512x512 pixels.

Images are organized under directories:

/kaggle/input/dog-vs-cat/animal/dog

/kaggle/input/dog-vs-cat/animal/cat

Approach

Data Augmentation to enhance the training set.

CNN and Transfer Learning models for classification.
