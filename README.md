# Brain Tumor Classification using ResNet18

This project classifies MRI brain scans into four categories using a fine-tuned ResNet18 neural network with grayscale input. It uses transfer learning and performs training with validation support.

## Dataset

The dataset used is from Kaggle:  
🔗 [Brain Tumor MRI Dataset by Masoud Nickparvar](https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset)

It includes four classes:
- Glioma
- Meningioma
- Pituitary tumor
- No tumor (healthy)

## How to Use

1. Clone this repository.
2. Place the dataset in appropriate `train/` and `test/` folders.
3. Open the `.ipynb` notebook in Google Colab or Jupyter and run the cells.

## Requirements

- Python 3.x
- PyTorch
- torchvision
- scikit-learn
- PIL

Install dependencies:

```bash
pip install torch torchvision scikit-learn
```

## If you need the trained model weights (best_model.pth), feel free to email me at:
📧 k.prabhav2005@gmail.com
