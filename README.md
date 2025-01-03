# ConfidenceVision

This is a simple web application for classifying images using a pre-trained convolutional neural network (CNN) model. The application allows users to select an image file from their file system and provides predictions on the content of the image.

## Dataset Information

The model used in this project is trained on the CIFAR-10 dataset. CIFAR-10 is a well-known dataset commonly used for image classification tasks. It consists of 60,000 32x32 color images in 10 classes, with 6,000 images per class. The classes are as follows:

1. Airplane
2. Automobile
3. Bird
4. Cat
5. Deer
6. Dog
7. Frog
8. Horse
9. Ship
10. Truck

The dataset is divided into 50,000 training images and 10,000 test images.

## Requirements

- Python 3.x
- TensorFlow
- PIL (Python Imaging Library)
- Image files for testing

## Installation

1. Install Python 3.x from [Python's official website](https://www.python.org/).
2. Install required dependencies using pip:

    ```
    pip install -r requirements.txt
    ```

3. Ensure you have some sample images for testing placed in the project directory.

## Usage

1. Run the `app.py` script.
2. The web application will open.
3. Use the file selector to choose an image from your file system.
4. The application will display the selected image and provide a prediction on its content.
5. The prediction will be shown along with the probability of the prediction.

## Screenshots
![wireframe](Frontend.png)
![Result1](result.png)



## Credits

- The Web Application is built using the Flask library.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
