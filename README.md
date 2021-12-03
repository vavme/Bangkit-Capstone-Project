# Bangkit-Capstone-Project
SMART APP TO DETECT DISEASES in PADDY <br/>
B21-CAP0470 - Alacritty Team <br/>

Background
==========
<h3>Population Grows But Production Fell</h3>

![image](https://user-images.githubusercontent.com/67742339/144524398-f440df29-8794-4193-b555-5f80b8f5838c.png)

![image](https://user-images.githubusercontent.com/67742339/144524402-ded46cbf-06b4-4aab-8895-d661ee4dca4d.png)

![image](https://user-images.githubusercontent.com/67742339/144524405-9703db81-4b84-4b88-a96a-3c46a62cc1fe.png)

There are several causes related to that but one of the causes/problems that we highlighted is :

![image](https://user-images.githubusercontent.com/67742339/144524478-99269dc1-f610-4592-9505-5bc03d58585f.png)

<br/>
Our main objective is to minimize human error and detect the diseases as early as possible. By detecting the diseases early, farmer could trim and sterilize the infected parts to stop and avoid the spread of the diseases infection which could lead into harvest failure.<br/>

The Model that is used
======================
To detect rice diseases, we use a CNN model. Our CNN model is based on pre-trained VGG19 architecture. To create the model specific to solve the problem we want to solve, we added some layers on top of the VGG19 model and trained it using the dataset we got before. Our model has six classes as the outputs. <br/>
The model could detect whether the crop is healthy or infected by one of the 5 diseases :  Blast, Blight, Tungro, Brown Spot and Hispa. <br/>
<h3>Accuracy and Loss</h3>
~70% Validation Accuracy <br/>

![image](https://user-images.githubusercontent.com/67742339/144524766-ad4b7a49-eb20-4b04-86f3-206be882a8b3.png)

![image](https://user-images.githubusercontent.com/67742339/144524793-ef50c7c8-03e5-4a53-82b2-7052f1d822fd.png)

