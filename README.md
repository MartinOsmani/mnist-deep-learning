# MNIST Deep Learning — FCNet vs CNN

Exploring fully connected and convolutional neural network architectures on the MNIST handwritten digit dataset using PyTorch.

## What's covered
- **Overfitting analysis** — visualising train/validation divergence
- **L2 regularisation sweep** — identifying optimal weight decay
- **Learning curve experiment** — validation error vs. training set size
- **Architecture comparison** — FCNet vs. CNN across all dataset sizes

## Results
| Model | Validation Error (60k training samples) |
|-------|------------------------------------------|
| FCNet | ~8.9% |
| CNN   | ~3.5% |

The CNN consistently outperforms the FCNet, with the gap widening at smaller training set sizes.

## Stack
Python · PyTorch · torchvision · NumPy · Matplotlib
