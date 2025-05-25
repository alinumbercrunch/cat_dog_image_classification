# Cat vs Dog Image Classification

This project is a simple deep learning classifier that distinguishes between images of cats and dogs using PyTorch.

## Features

- Trains a neural network to classify images as either "cat" or "dog"
- Includes scripts for training and making predictions
- Example code for loading and testing with your own images

## Project Structure

cat_dog_rec/
├── train.py # Script to train the model
├── predict.py # Script to make predictions on new images
├── model.pth # Saved trained model (not included by default)
├── requirements.txt # Python dependencies
└── README.md # Project documentation


## Getting Started

1. **Clone the repository:**


2. **Install dependencies:**


3. **Train the model:**


4. **Make predictions:**
Place your test images in a directory (e.g., `~/Desktop/`) and update the image paths in `predict.py`. Then run:


## Requirements

- Python 3.8+
- PyTorch
- torchvision
- Pillow (PIL)

## Notes

- Make sure your images are accessible to your script (see instructions above for WSL users).
- The trained model weights (`model.pth`) are not included by default. Train the model or add your own weights.

## License

This project is open source and available under the [MIT License](LICENSE).
