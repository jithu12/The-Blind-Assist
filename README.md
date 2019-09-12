# The-Blind-Assist

This project is based on the RBI's [tender](https://github.com/joshi98kishan/The-Blind-Assist/blob/master/RFP03052019.pdf) titled "Development of Mobile Application for Aiding the Visually Impaired in Identifying the Denominations of Indian Banknotes (Currency Denomination Identifier)" which was released on May 04, 2019.

Which will help visual and hearing-impaired persons to detect the Indian Currency Denomination by clicking the image of a banknote through this android app.

This is a major project which is based on (Research + Applied) machine learning and Android Development. 

We created the Indian Currency Dataset(ICD) for this project which currently has 6000 images. ICD is a very rich dataset, which contains very diverse images. We have covered all the classes (none, 5, 10, 20, 50, 100, 200, 500, 2000). Also, we have covered all kind of note's images like older and newer, front and rear, in different lighting conditions etc.

(We will share the dataset after the completion of the project.)

We are using Keras, TensorFlow, Fastai and PyTorch libraries, to leverage the power of all.       
Currently, we have achieved 99% accuracy on ResNet50 and 90% accuracy on MobileNetV2 model (DATE : 12/9/2019).

We are using MobileNet model because it runs efficiently and fast on mobile phones.

[DATE : 12/9/2019]

![alt text](https://github.com/joshi98kishan/The-Blind-Assist/blob/master/sample_images/sample_3.jpeg)

(Initially we have used googles examples app, added our tflite model to it)

(We will modify the app according to our use case)
