# Background Remover

This project demonstrates three methods for removing the background from images using various Python libraries and techniques.

## Methods

### Method 1: Using `rembg` Library

1. Install the required library: `rembg`
2. Use the `remove` function from `rembg` to remove the background
3. Save and display the result

### Method 2: Using `mediapipe` Library

1. Install the required library: `mediapipe`
2. Use the `SelfieSegmentation` model from `mediapipe` to segment the foreground
3. Apply the segmentation mask to remove the background
4. Save and display the result

### Method 3: Using `deeplabv3` Model from PyTorch

1. Load the `deeplabv3_resnet50` model from PyTorch
2. Preprocess the input image and generate a segmentation mask
3. Create a transparent foreground image using the mask
4. Save and display the result

## Requirements

- Python 3
- `rembg`
- `mediapipe`
- `opencv-python`
- `torch`
- `torchvision`
- `PIL`
- `matplotlib`
- `numpy`

## Running the Notebook

1. Clone the repository and navigate to the project directory:

    ```bash
    git clone https://github.com/DarkLord-13/Machine-Learning-01.git
    cd Machine-Learning-01
    ```

2. Open the `Background_Remover.ipynb` notebook in Jupyter Notebook or Google Colab.

3. Follow the code cells in the notebook to install the necessary libraries, load the models, and run the background removal methods.

## Author

**Nishant Kumar**

Feel free to fork the project and raise an issue if you have any questions or suggestions.
