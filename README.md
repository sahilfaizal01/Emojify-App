# Emojify-App
Creating emojis based on facial emotions using deep learning.

## Dataset:
* Source:- Kaggle 
* Name:- FER-2013 dataset
* Contents:- train and test directories
* Link:- https://www.kaggle.com/datasets/msambare/fer2013
* Classes:- 7 (Angry, Happy, Sad, Disgust, Fearful, Neutral, Surprise)

## Images:
### Angry
![PrivateTest_20887918](https://user-images.githubusercontent.com/106440078/211151893-b050e0f3-e244-4649-953a-c77ed32c0f80.jpg)

### Happy
![PrivateTest_647018](https://user-images.githubusercontent.com/106440078/211151904-2922f521-0cdf-4c9d-b2a6-f9bce15a45bf.jpg)

### Sad
![PrivateTest_3246395](https://user-images.githubusercontent.com/106440078/211151922-ddbc76a7-705c-4f70-849b-6df4defdb9fc.jpg)

### Disgust
![PrivateTest_3881740](https://user-images.githubusercontent.com/106440078/211151939-1133b239-eef9-426b-b56f-6c197fa56fab.jpg)

### Fearful
![PrivateTest_4212136](https://user-images.githubusercontent.com/106440078/211151957-7affbb8a-d76d-49ab-9dfc-2c9db96b9a80.jpg)

### Neutral
![PrivateTest_1791924](https://user-images.githubusercontent.com/106440078/211151965-155ec01c-f84e-44dc-a1f2-b7944b90cfbc.jpg)

### Surprise
![PrivateTest_914251](https://user-images.githubusercontent.com/106440078/211151973-9501cc5f-90ac-4fc5-945d-4d7f11b05d24.jpg)

## Steps Involved:
* Download the dataset
* Build a classifier
* Save the model weights
* Load the weights
* Download and load HAAR Cascade inference file for frontal face - to detect human faces
* Crop out the face and make prediction 
* Print the detected emotion on the video frame
* Based on the emotion find the corresponding emoji
* Built a Twinkter app
* Map the detected face and emoji for OUTPUT

## Project Contents:
* app.ipynb -> main file
* fer2013-classification.ipynb -> classifier file
* model.h5 -> weight file
* haarcascade_frontalface_default.xml -> haar file

## Classifier Performance:
* Training Accuracy: 82%
* Testing Accuracy: 58%
* Note:- Overfitting
### Accuracy vs Epoch Plot
![image](https://user-images.githubusercontent.com/106440078/211152254-779b3705-f38a-47c0-9993-10e1a6bfbe94.png)
### Loss vs Epoch Plot
![image](https://user-images.githubusercontent.com/106440078/211152273-23ff35b7-d6e1-461c-b84a-fa1e47feafb3.png)

## Libraries Needed:
* Numpy
* Matplotlib
* Pandas
* Tensorflow
* Keras
* PIL
* Twinkter

## Result:
![result](https://user-images.githubusercontent.com/106440078/211151269-2be88df4-7364-49bf-9eb7-4246209cb0e2.png)
