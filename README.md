# Facial-Expression-Recognition
This project is a part of Coursera's Guided Project - [Facial Expression Recognition with Keras](https://www.coursera.org/programs/86ebe3a1-8523-43c0-a9da-7374390c1e9a/browse?entityTypeDescription=Rhyme+Projects&index=prod_enterprise_products&productId=IC9GxmJ7EeqZhwpHN8ICRw&productType=course&query=computer+vision+&showMiniModal=true)

In this project, we will build and train a convolutional neural network (CNN) in Keras from scratch to recognize facial expressions. The data consists of 48x48 pixel grayscale images of faces. The objective is to classify each face based on the emotion shown in the facial expression into one of seven categories (0=Angry, 1=Disgust, 2=Fear, 3=Happy, 4=Sad, 5=Surprise, 6=Neutral). We will use OpenCV to automatically detect faces in images and draw bounding boxes around them. Once we have trained, saved, and exported the CNN, we will directly serve the trained model to a web interface and perform real-time facial expression recognition on video and image data.

The project can be braodly divided into two parts -
1) Build and train a model in Keras for Facial Expression Recognition.
2) Deploy the model on web using FLASK and run it on videos.

# Steps to follow

1) Extract train and test images from ```data.rar``` file.
2) Install dependencies using

   ```pip install pipenv```

   ```pipenv install```

3) Run the jupyter notebook for training, ```model.json``` and ```model_weights.h5``` files will be created after training.
4) Add the correct path to the video file in camera.py on line 11.
5) Now run  ```pipenv run python3 main.py```
