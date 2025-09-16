# ViT-CIFAR10 Fine-Tuning

This project fine-tunes the `google/vit-base-patch16-224` Vision Transformer on the CIFAR-10 dataset using Hugging Face Transformers.

## Results
- Test Accuracy: **87%** (3 epochs, batch size 32)

## How to Run
```bash
pip install -r requirements.txt
python vit_cifar10.py
