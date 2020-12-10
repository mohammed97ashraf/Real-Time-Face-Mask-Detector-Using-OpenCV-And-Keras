# Real-Time-Face-Mask-Detector-Using-OpenCV-And-Keras

## **Overview**
Coronavirus has now become the talk of the town, most people in the world right now are suffering badly and every day thousands of people are dying because of COVID-19. As per WHO, face masks combined with other preventive measures such as frequent hand-washing and social distancing help slow down the spread of the coronavirus.

In this project we will build a real-time system to detect whether the person is on the webcam wearing mask or not.

![result](https://github.com/mohammed97ashraf/Real-Time-Face-Mask-Detector-Using-OpenCV-And-Keras/blob/main/ezgif.com-gif-maker.gif)

## **Requirement**
### Things you need to install 
1. Python 3.9
     * This setup requires that your machine has python 3.9 installed on it. you can refer to this url https://www.python.org/downloads/ to download python. Once you have python downloaded and installed, you will need to setup PATH variables (if you want to run python program directly, detail instructions are below in how to run software section). To do that check this: https://www.pythoncentral.io/add-python-to-path-python-is-not-recognized-as-an-internal-or-external-command/.
2. You will also need to download and install the required packages after you install python 
     * Sklearn (scikit-learn)
     * numpy
     * tensorflow
     * keras
     * cv2
     * imutils
3. To install the Packages
```Language
pip3 install -U scikit-learn
pip3 install numpy
pip3 install opencv-python
pip install tensorflow
pip3 install Keras
pip3 install imutils
```
4. Or else use can download anaconda and use its anaconda prompt to run the commands. To install anaconda check this url https://www.anaconda.com/download/. most the Packages are preinstalled in the anaconda environment.But you need install some of the Packages
      * Keras
        * conda install -c conda-forge keras
      * opencv
        * conda install -c conda-forge opencv

## **Dataset**
The dataset we are working on was downloaded from Kaggle(https://www.kaggle.com/niharika41298/withwithout-mask?select=maskdata).There are two folders in the maskdata folder. One folder contains a mixture of images for training and the other for testing.

## **How To Run**
1. The first step would be to clone this repo in a folder in your local machine. To do that you need to run following command in command prompt or in git bash
```Language
$ git clone  https://github.com/mohammed97ashraf/Real-Time-Face-Mask-Detector-Using-OpenCV-And-Keras.git
```
2. This will copy all the data source file, program files and model into your machine.

3. Open the train.py file and run/execute .
4. Then Open the test.py in this you need to change the 'haarcascade_frontalface_default.xml' link according to your location
```python
# We load the xml file
classifier = cv2.CascadeClassifier('C:/Users/Ashraf/anaconda3/pkgs/libopencv-4.0.1-hbb9e17c_0/Library/etc/haarcascades/haarcascade_frontalface_default.xml') #change the link according  to your directory
```
5. After changeing the 'haarcascade_frontalface_default.xml' Link Now you can run the test.py 

