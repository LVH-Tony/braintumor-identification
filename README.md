# 🧠 Brain Tumor Image Classifier 🏥

This project is about building a Brain Tumor Image Classifier using Convolutional Neural Networks (CNNs) and Transfer Learning.

## 📝 Project Overview

The project uses a dataset of brain images stored in a structured folder. The images are extracted in an auto-labelled fashion using Keras' `flow_from_directory`. The images are of different sizes, which is a problem for CNNs as they expect all images to have the same size. Therefore, the images are cropped from the center to ensure they all have the same size. Data Augmentation is used to generate more training data.

## 🚀 Setup

### Requirements

- Python 3.6 or above 🐍
- TensorFlow 2.0 or above 🧠
- Keras 🧪
- Matplotlib 📊
- Numpy 🧮

### Installation

1. Clone the repository:

```bash
git clone https://github.com/LVH-Tony/braintumor-identification.git
cd braintumor-identification
```

2. Install the required packages:

```bash
pip install -r requirements.txt
```

## 🛠️ Usage

1. Prepare your dataset by placing your images in a structured folder. The images should be auto-labelled and extracted using Keras' `flow_from_directory`.

2. Run the script:

```bash
python brain_tumor_classifier.py
```

## 🤖 Models

Two models are used in this project:

1. A custom Convolutional Neural Network (CNN) model.
2. A model built using Transfer Learning with VGG16.

## 📈 Results

The custom CNN model achieved a training accuracy of ~95% and a testing accuracy of ~72%. The Transfer Learning model achieved a training accuracy of ~98% and a validation accuracy of ~91%.

## 👥 Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## 📜 License

[MIT](https://choosealicense.com/licenses/mit/)
