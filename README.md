# Sign Language Detector
A simple for detecting hand  sign language.
Here, we have implemented CNN (Convolution Neural Network) using Keras.

### Tools Used
1. Python 3
2. OpenCV 3
3. Tensorflow
4. Keras
5. cnn (Convolution Neural Network) model 

### How to run this project
1. Install Python 3, Opencv 3, Tensorflow, Keras.
2. First Train the model.
    ```
    python cnn_model.py

    after successfull training we get "Trained_model.h5" which used to recognize the gestures.
    ```
2. Now to test the model you just need to run single.py . To do so just open the terminal and run following command.
    ```
    python single.py
    ```
    Adjust the hsv values from the track bar to segment your hand color.
    this will recognize the gesture from image that is named as 1.png in directory

3. Select image from file and recognize it.
    ```
    python filechoose.py

    run this file and select any image from dataset it will give gestrure extracted from that image.
    ```
4. Create own dataset.
    ```
    to create your own dataset for recognition run the following file

    python capture.py

    and then enter gesture name like 'a'
    and adjust the hsv values from the track bar to segment your hand color.
    and click button 'c' continuously to capture images.
    it will capture 1750 images in  training_set and 250 images in test_set.
     
    ```
5. Run finalsource.py file to run project with GUI

6. Links 
    https://www.edureka.co/blog/convolutional-neural-network/
https://youtu.be/qVzJ92SlFpI