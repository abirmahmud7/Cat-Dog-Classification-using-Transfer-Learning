# Cat-Dog-Classification-using-Transfer-Learning
<br>

A Convolutional Neural Network (CNN) project built with TensorFlow/Keras that classifies images of cats and dogs. The project utilizes **Transfer Learning** with a pre-trained VGG16 base and implements an optimized data pipeline to achieve over **90% validation accuracy** without overfitting.

##  Key Features
Transfer Learning: Leverages a frozen VGG16 base pre-trained on ImageNet.
Overfitting Control: Implements Keras Preprocessing Layers for real-time Data Augmentation (flips, rotations, zooms) and a Dropout layer (35%) to ensure excellent model generalization.
Robust Image Filtering:Includes a custom script using TensorFlow's strict image decoder to scan, flag, and remove corrupt image data (addressing common broken file exceptions.

##  Built With
* Python
* TensorFlow / Keras
* NumPy
* Matplotlib

##  Credits & Acknowledgments
This project was built for educational and learning purposes. I took guidance and help for setting up the baseline steps from a fantastic YouTube tutorial by the channel **CampusX**.
