# 🐱🐶 Cats vs. Dogs Classification with CNN and ResNet

This project provides a practical comparison between two prominent deep learning architectures—Convolutional Neural Networks (CNN) and Residual Networks (ResNet)—applied to the task of classifying images of cats and dogs. The repository contains all the code necessary to train, evaluate, and visualize these models, as well as supporting materials such as Grad-CAM visualizations and performance metrics.

## 📂 Project Structure
```bash
├── data/                   # Folder for dataset storage (if applicable)
├── notebooks/              # Jupyter notebooks with experiments
├── models/                 # Trained models
├── scripts/                # Python scripts for training and evaluation
├── README.md               # Project overview and instructions (this file)
└── requirements.txt        # Required libraries
```

## 📙 Dataset

- **Source**: [Kaggle Cats vs Dogs dataset](https://www.microsoft.com/en-us/download/confirmation.aspx?id=54765)
- **Size**: 25,000 images (cats and dogs)
- **Preprocessing**: Images are resized to 128x128 pixels, with image preprocessing applied.

## 🧪 Experiments

The training experiments consist of two models trained on the Kaggle Cats vs. Dogs dataset using identical hyperparameters. The repository includes:

- Grad-CAM visualizations for analyzing model interpretability.
- Confusion matrices and classification reports to evaluate performance.
- A comparison of training/validation curves for accuracy and loss between CNN and ResNet.

  

## How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/leonardo-reginato/cnn-vs-resnet.git
   cd cnn-vs-resnet
   ```
2. Install the required dependencies:
  ```bash
  pip intall -r requirements.txt
```
3. Run
   - notebooks/cats_dogs_task.ipynb

   
## 📊 Results

- Accuracy: ResNet outperformed CNN with ~94% validation accuracy, while CNN stabilized around ~90%.
- Grad-CAM: ResNet distributed attention more evenly across the image, while CNN focused on prominent features like the eyes and face.
- Trainable Parameters: Despite its deeper architecture, ResNet had fewer parameters (~4.6M vs ~5.1M for CNN) due to its efficient use of residual blocks.

## 🧠 Key Learnings

- ResNet’s residual connections allow for deeper networks, avoiding vanishing gradients and reducing overfitting risks.
- CNN, while simpler, requires more parameters for similar performance and tends to overfit on small datasets.


## Licence
This is licensed under the MIT licence.
