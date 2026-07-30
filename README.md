# 🎭 Realistic Human Face Generation using GAN

A deep learning project that generates realistic human face images using a **Generative Adversarial Network (GAN)**. The model is trained on the **CelebA** dataset and learns to create synthetic human faces from random noise through adversarial training between a Generator and a Discriminator.

## 🚀 Features

- Generate realistic human face images.
- Train a Deep Convolutional GAN (DCGAN).
- Preprocess the CelebA dataset.
- Visualize generated images during training.
- Monitor Generator and Discriminator losses.
- Save the trained Generator model.
- GPU-accelerated training on Kaggle.

## 🛠 Technologies

- Python
- TensorFlow / Keras
- NumPy
- OpenCV
- Matplotlib
- Kaggle Notebook

## 📂 Dataset

The project uses the **CelebA (CelebFaces Attributes Dataset)**.

Preprocessing steps include:

- Image loading
- Face resizing
- Pixel normalization
- Batch generation

## 🧠 Model Architecture

### Generator

- Dense Layer
- Batch Normalization
- Reshape Layer
- Conv2DTranspose Layers
- ReLU Activation
- Tanh Output Layer

### Discriminator

- Conv2D Layers
- LeakyReLU Activation
- Dropout
- Flatten Layer
- Sigmoid Output Layer

## 📈 Training

The Generator creates fake face images from random latent vectors while the Discriminator learns to distinguish between real and generated images. Both networks improve through adversarial learning until the Generator produces highly realistic faces.

## 📊 Results

The notebook displays:

- Generated face samples during training
- Generator and Discriminator loss curves
- Final generated face images

## ▶️ How to Run

1. Open the notebook in Kaggle.
2. Enable **GPU** from the notebook settings.
3. Run all cells sequentially.
4. Wait for the training process to complete.
5. View the generated face images.

## 📁 Project Structure

```text
.
├── Realistic Human Face Generation using a GAN.ipynb
├── README.md
└── requirements.txt
```

## 📚 Learning Outcomes

- Generative Adversarial Networks (GANs)
- Deep Convolutional GAN (DCGAN)
- Image preprocessing
- Adversarial training
- Deep learning for image generation
- TensorFlow/Keras implementation

## 📄 License

This project was developed for educational purposes.
````
