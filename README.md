# Grad-CAM Implementation

This repository contains implementations of Grad-CAM (Gradient-weighted Class Activation Mapping) for visualizing deep learning models' decision-making processes. Grad-CAM is applied using pre-trained models like ResNet18 and VGG16 to generate class activation maps, which highlight the regions in an input image most relevant to a model's predictions.

## Table of Contents
- [Notebooks](#notebooks)
- [Installation and Setup](#installation-and-setup)
- [License](#license)

## Notebooks

1. **gradCAM_resnet.ipynb**
    - Applies Grad-CAM using a pre-trained ResNet18 model.
    - Generates CAM (Class Activation Maps) for a provided image using the last layer of the ResNet model.
    - Visualizes the overlay of the heatmap with the original image.

2. **gradCAM_nose_detection.ipynb**
    - Focuses on detecting keypoints (e.g., nose, eyes) using Grad-CAM.
    - Utilizes a pre-trained ResNet18 model and generates CAMs for specific classes.
    - Demonstrates visualization for regions like the nose or eyes in an image.

3. **gradCAM_vgg.ipynb**
    - Demonstrates the use of Grad-CAM on a pre-trained VGG16 model.
    - Generates CAMs for both the first and last convolutional layers.
    - Compares the heatmaps and their respective overlays with the original image.

## Installation and Setup

To run the notebooks, you’ll need the following dependencies:

- Python 3.x
- PyTorch
- Torchvision
- NumPy
- Matplotlib
- Pillow (PIL)
- OpenCV

You can install the dependencies using `pip`:

```bash
pip install torch torchvision numpy matplotlib Pillow opencv-python
```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Feel free to reach out if you encounter any issues or want to contribute!
