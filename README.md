# Face-Mask-Detector

###### Face Mask Detector built with OpenCV, TensorFlow/Keras using Deep Learning CNN and Computer Vision concepts in order to detect face masks in static images as well as in real-time video streams.
###### The face mask detector didn't use any morphed masked images dataset. The model is accurate, and since the MobileNetV2 architecture is used, it’s also computationally efficient and thus making it easier to deploy the model to embedded systems (Raspberry Pi, Google Coral, etc.).

### :stars:TeachStack/framework used
- [OpenCV](https://opencv.org/)
- [Keras](https://keras.io/)
- [TensorFlow](https://www.tensorflow.org//)
- [MobileNetV2](https://arxiv.org/abs/1801.04381)

### :file_folder: Dataset
###### This dataset consists of 3833 images belonging to two classes:

 - ###### with_mask: 1915 images
 - ###### without_mask: 1918 images

###### The images were collected from the following sources:

 - ######  Kaggle datasets
 
### :key: Prerequisites
###### All the dependencies and required libraries are included in the file       ``` requirements.txt ``` Run the following command in your Terminal/Command Prompt to install the libraries required

``` 
     $ pip3 install -r requirements.txt
```

### :bulb: Working

1. ###### Open terminal. Go into the cloned project directory and type the following command:

```
   $ python3 train_mask_detector.py --dataset dataset
```
2. ###### To detect face masks in real-time video streams type the following command:

```
  $ python3 detect_mask_video.py 
```

### :label: Streamlit app
###### Face Mask Detector webapp using Tensorflow & Streamlit

###### command

```
   $ streamlit run app.py 
```
