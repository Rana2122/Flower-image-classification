# 🌸 Flower Image Classification with TensorFlow & Gradio

This project is a simple **Deep Learning image classifier** that identifies five types of flowers using a Convolutional Neural Network (CNN). It is built using TensorFlow and deployed with an interactive Gradio UI.

---

## 📁 Dataset

We use the **[TensorFlow Flower Dataset](https://storage.googleapis.com/download.tensorflow.org/example_images/flower_photos.tgz)** which contains images of:
- Daisies
- Dandelions
- Roses
- Sunflowers
- Tulips

The dataset is automatically downloaded and split into training and validation sets.

---

## 🧠 Model Architecture

The model is a custom CNN consisting of:

- Rescaling Layer
- Conv2D + MaxPooling (x3)
- Flatten Layer
- Dense (128 units)
- Dense output layer with softmax activation

---

## 🚀 How to Run (Google Colab)

1. Open this notebook in Google Colab: [Flower Classifier on Colab](https://colab.research.google.com/)
2. Run all cells step-by-step.
3. Train the model for ~10 epochs.
4. Launch the Gradio interface to classify your own flower images.

---

## 🧪 Example Usage

Once trained, use the Gradio UI:

- Upload an image of a flower.
- The model will return prediction probabilities for each flower class.


## 📦 Dependencies

- TensorFlow
- Gradio
- NumPy
- PIL (Pillow)

To install:

```bash
!pip install tensorflow gradio pillow numpy
