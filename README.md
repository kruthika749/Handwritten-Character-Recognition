# Handwritten-Character-Recognition
A powerful yet easy-to-use Handwritten Character Recognition system built with PyTorch, CNNs, and Streamlit.
This project allows users to upload handwritten digits or letters and get instant predictions using a trained deep learning model.
The app supports both MNIST digits and EMNIST balanced character sets, handles orientation fixes, auto-detects model size, and provides top-k predictions with confidence scores.
 Features
* Deep Learning Model (CNN)
*Custom-built Convolutional Neural Network in PyTorch
*Automatically adapts to any number of output classes
*Supports digits (0–9), uppercase/lowercase letters, and EMNIST balanced labels
*Smart Image Preprocessing
*Automatically performs:
*Grayscale conversion
*Inversion (white text on black background)
*Thresholding to remove noise
*Auto-cropping around the character
*Resizing to 28×28
*Centering on a square canvas
*EMNIST orientation correction (rotate + mirror)
* Prediction System
*Live model loading using .pth checkpoint
*Softmax confidence
*Easily switch between MNIST and EMNIST preprocessing modes
*Clear, friendly output with confidence percentages
Make sure Python 3.9+ is installed.
1️⃣ Install dependencies
pip install streamlit torch torchvision pillow numpy
pip install matplotlib
▶️ Run the Application
Inside your project folder:
streamlit run app.py
