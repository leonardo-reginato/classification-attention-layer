# Cats vs Dogs Classification with Attention Layers

This project compares CNN models for classifying images of cats and dogs, with and without attention layers, to evaluate the performance improvement from using attention mechanisms.

## Project Overview

We explore two models:
- **Baseline CNN**: A traditional CNN.
- **CNN with Attention**: A CNN enhanced with an attention layer to improve focus on relevant image parts.

## Dataset

- **Source**: [Kaggle Cats vs Dogs dataset](https://www.microsoft.com/en-us/download/confirmation.aspx?id=54765)
- **Size**: 25,000 images (cats and dogs)
- **Preprocessing**: Images are resized to 150x150 pixels, with augmentation techniques applied.

## How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/leonardo-reginato/classification-attention-layer.git
   cd cats-dogs-classification-attention-layer
   ```
2. Install the required dependencies:
  ```bash
  pip intall -r requirements.txt
```
3. Download and place the data in the data/ directory.
4. Run the script to train the models:
   ```bash
   python script/train_model.py
   ```
## Results
- **Accuracy**: The model with attention layers may improve accuracy in image classification.
- **Training Time**: The attention model may have longer training time due to added complexity.

## Licence
This is licensed under the MIT licence.
