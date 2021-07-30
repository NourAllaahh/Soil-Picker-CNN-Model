# Soil Picker CNN Model
 A CNN Model used to scan soil to detect its type to later give suggestions to crops to be planted in this soil, this Model is integrated in E-Farming mobile application and here are screenshots of the function used by this model inside the application:

<img src="https://user-images.githubusercontent.com/72973609/127660820-67ad1946-45b6-4d61-9c23-4f820cfaaa4c.jpg" alt="alt text" width="200" height="400"> <img src="https://user-images.githubusercontent.com/72973609/127660823-0091371c-8577-42ea-84e2-75186f228766.jpg" alt="alt text" width="200" height="400"> <img src="https://user-images.githubusercontent.com/72973609/127660833-6760ba41-1e9e-475d-a900-74a98c2af1f3.jpg" alt="alt text" width="200" height="400">

## Methodolgy 

Data Gathering:

* For The Soil Type Detection:
we used a publicly available Dataset [“Soil Types Dataset”](https://www.kaggle.com/prasanshasatpathy/soil-types)
This Dataset Contains images of Soil Types collected under different environment Conditions, Pictures of Soils are divided into the following: 
Black Soil, Cinder Soil, Peat Soil, Laterite Soil , Yellow Soil. Here are the generate Dataset Classes:
<img src="https://user-images.githubusercontent.com/72973609/127662912-e814f58a-d7a2-4e4a-8771-ff646ed30c3b.png" alt="alt text" width="300" height="200">


## Techniques:

Convolutional Neural Network: is a class of deep neural networks, most applied to analyzing visual imagery. its widely used in applications of image and video recognition.

<img src="https://user-images.githubusercontent.com/72973609/127575041-c73b3e28-9510-465d-8c8b-7ac991f5546e.png" alt="alt text" width="500" height="200">

## Creation and Compilation

* Pre-process The Images is an improvement of the image data that suppress undesired distortions or enhances some image features important for further processing.

<img src="https://user-images.githubusercontent.com/72973609/127662955-81854c2c-380e-40ff-8697-ba10d3af87ad.png" alt="alt text" width="400" height="300">

* Build Convolutional Neural Network with Type of layers (Conv2D, MaxPooling2D, Flatten, Dense….) 
<img src="https://user-images.githubusercontent.com/72973609/127662967-6ef0565b-0cf3-4027-bdaf-e7275c5d153d.png" alt="alt text" width="400" height="300">
<img src="https://user-images.githubusercontent.com/72973609/127663006-28896672-2d7c-4ed6-87f0-c239e46eeeb7.jpg" alt="alt text" width="400" height="300">

* Sample of Input after each Layer 

<img src="https://user-images.githubusercontent.com/72973609/127664145-902f1420-46b0-44c9-a364-3136ca6eb17a.png" alt="alt text" width="400" height="300">


* Train The Model results and got accuracy 0.9479

<img src="https://user-images.githubusercontent.com/72973609/127664258-42bbbc5a-ddde-4349-8659-781b5ec1def2.png" alt="alt text" width="400" height="300">

* Plot Graphs for Training Accuracy and Training Loss

<img src="https://user-images.githubusercontent.com/72973609/127664268-91c5a7e4-3901-4921-a82a-93a57decaa78.png" alt="alt text" width="200" height="200"> <img src="https://user-images.githubusercontent.com/72973609/127664277-801daccb-fcf7-4622-b497-d03d8f477106.png" alt="alt text" width="200" height="200">


