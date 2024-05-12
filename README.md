# Computer-Vision-Project ##########################################
Project in Computer Vision - COE 49413 - 01 || Project Group 7
Fatima Sha'al / MHD Maen Khaskieh

####################################################################

How to run the code step by step for both training and testing cases:

Prerequisites:
  Python 3.6+
  PyTorch 1.7+
  TorchVision
  Albumentations
  OpenCV
  tqdm
  NumPy
  scikit-learn
  Matplotlib

Install all required libraries using pip:
pip install torch torchvision albumentations opencv-python tqdm numpy scikit-learn matplotlib

Clone the project repository to the local machine

Download and Prepare the Dataset
Ensure that your dataset is structured as follows:
data/
├── train/
│   ├── Bacterial Pneumonia/
│   ├── Corona Virus Disease/
│   ├── Normal/
│   ├── Tuberculosis/
│   └── Viral Pneumonia/
├── val/
│   └── [Same structure as train]
└── test/
    └── [Same structure as train]

Download te 4 models in the files on this repository:
  EffiecientNet_B0
  MobileNet-v2
  ResNet
  SqueezeNet

Run the files
