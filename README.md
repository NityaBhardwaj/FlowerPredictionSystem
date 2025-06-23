
# PetalVision: A Flower Classifier in Python
This mini-project is a flower classification system built using Python and machine learning techniques. The project uses a dataset of flower images and trains a model to recognize and classify different types of flowers based on their visual features.


## Appendix
📚 Dependencies
To run this project, make sure you have the following Python packages installed:

numpy

pandas

matplotlib

tensorflow or keras

sklearn

opencv-python (if image preprocessing is done manually)

##Dataset

Source: Kaggle – “Flowers Recognition” by Alexander Mamaev 

Total images: 4,242 labeled flower images 

Classes: 5 types – daisy, dandelion, rose, sunflower, tulip 

Images per class:

Dandelion: ~1,052

Rose: ~784

Tulip: ~984

Daisy: ~764

Sunflower: ~733 

Image resolution: ~320×240 pixels 

🧠 ##Model Architecture

Base model: Custom CNN or ResNet‑9 (built from scratch).

Transfer learning option: ResNet‑34 (pretrained) for improved performance.

Layers: Convolution + BatchNorm + ReLU, with residual blocks and classifier head.

Optimizer: Adam (or SGD); Loss: Cross‑entropy.
#


![Sunflower Scan](images/sunflower_scan.jpg)


