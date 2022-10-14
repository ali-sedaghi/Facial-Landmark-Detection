# Facial-Landmark-Detection
Facial landmark detection on FER2013 dataset using Dlib and MTCNN

## Table of Contents

1. [Dataset](#dataset)
2. [Model Checkpoints](#model-checkpoints)
3. [Notebooks](#notebooks)
4. [Results](#results)


## Dataset

You can download FER2013 dataset from [Here](https://drive.google.com/drive/folders/1BBvH1i56yNsmSI1ngXA25JaKhWjkSg-e?usp=sharing)
You need to place ```fer-2013-images.npy``` in ```dataset``` folder


## Model Checkpoints

You can download model checkpoints and extracted landmarks from [Here](https://drive.google.com/drive/folders/1rOTG6mXDZKbyQwsoVv2DxqCmk_75b1lv?usp=sharing)
You need to place checkpoints in ```pose_model``` and ```face_detection_model``` folder


## Notebooks

1. [Dlib approach](notebooks/Dlib.ipynb)
2. [MTCNN approach](notebooks/MTCNN.ipynb)


## Results

Dlib            |  MTCNN
:-------------------------:|:-------------------------:
![Result-Dlib](https://user-images.githubusercontent.com/45814362/195947467-0d69a717-e6a8-42e0-b23b-fb3e8dcdf352.png) | ![Result-MTCNN](https://user-images.githubusercontent.com/45814362/195948128-539bb422-878a-4e0c-9e41-848f9e7a9da0.png)
