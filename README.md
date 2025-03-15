# **Dog vs Cat Image Classification**

**Project Overview**  
This project uses **Convolutional Neural Networks (CNNs)** to classify images of dogs and cats. The model pipeline includes **data augmentation** techniques to improve generalization and **transfer learning** using a pre-trained model for faster and more accurate classification.

---

## **Project Goals**
The goal of this project is to build a robust image classifier that distinguishes between dog and cat images. The steps include:

1. **CNN Architecture**: A custom CNN model is initially built.
2. **Data Augmentation**: Applied to increase the diversity of the training data through transformations like rotation, flipping, and zooming.
3. **Transfer Learning**: A pre-trained model (**VGG16**) is fine-tuned to improve performance.

---

## **Dataset**

- **Images**: 500 images of dogs and 500 images of cats, resized to 512x512 pixels.
- **Directory Structure**:
    - `/kaggle/input/dog-vs-cat/animal/dog`
    - `/kaggle/input/dog-vs-cat/animal/cat`

---

## **Approach**

1. **Data Augmentation**: Enhance the training set by applying various transformations like rotation, flipping, and zooming to improve model generalization.
2. **CNN and Transfer Learning**: Use a custom CNN and fine-tune the **VGG16** pre-trained model for classification.

---

**Technologies Used**:
- TensorFlow
- Keras
- Python
- NumPy
- Matplotlib

---

Feel free to clone the repository and try out the model for image classification tasks!
