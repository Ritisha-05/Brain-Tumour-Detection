#Brain Tumor Detection System Using Vision Transformer and CNN
#Project Overview
This project is focused on the detection of brain tumors using a combination of Vision Transformer (ViT) and Convolutional Neural Networks (CNN). The system is designed to analyze MRI scans to determine the presence of brain tumors. The Vision Transformer model is utilized for feature extraction, while the CNN model is used for the final classification.
#Features
Brain Tumor Detection: Automatically detects the presence of brain tumors in MRI scans.
Hybrid Model: Combines the power of Vision Transformers and CNNs for accurate detection.
Classification: Efficiently classifies images into tumor and non-tumor categories.
#Technologies Used
Vision Transformer (ViT): Used for feature extraction from MRI images.
Convolutional Neural Networks (CNN): Employed for image classification.
Python: The main programming language used.
TensorFlow/Keras: Deep learning frameworks used to implement the models.
NumPy, Pandas: Libraries for data manipulation and processing.
Matplotlib, Seaborn: Used for data visualization.
#Dataset
The MRI scan dataset used in this project is publicly available and consists of labeled brain images. The images are divided into two categories: tumor and non-tumor.
1.Clone the repository:

git clone https://github.com/your-username/Brain-Tumor-Detection.git

2.Navigate to the project directory:

cd Brain-Tumor-Detection

3.Install the required packages:

pip install -r requirements.txt

4.Run the model:

python main.py

#Usage:

1.Place the MRI images you want to analyze in the input/ directory.
2.Run the detection script using the command mentioned above.
3.The results will be displayed, indicating whether a tumor is present.

#Results:

The model has been trained on a set of MRI images, achieving a high accuracy in detecting brain tumors. Detailed performance metrics are available in the results/ directory.


