# Neural Style

This folder contains a joint project with Abdullah Alsalamah (@AbdullahAlsalamah) and Abeer Mayan (<abeermayan@gmail.com>). The project was part of the AI Artathon (<https://theglobalaisummit.com/artathon/>). The Artathon aims to generate art images using AI approaches. This project uses Neural Style (<https://arxiv.org/abs/1508.06576>) to generate art images by applying the style of some image (style image) to the content of another image (content image).

Our approach is to divide the content image into 4 parts. Then, a style is applied to each part of the content image. The following are: 
* Content Image:
![Content Image](https://github.com/Fahd94-sa/AI-generated-art/blob/master/Neural-Style/content.jpeg)

* The 4 parts of the content image are:
![First Part](https://github.com/Fahd94-sa/AI-generated-art/blob/master/Neural-Style/images/content1.jpeg)
![Second Part](https://github.com/Fahd94-sa/AI-generated-art/blob/master/Neural-Style/images/content2.jpeg)
![Third Part](https://github.com/Fahd94-sa/AI-generated-art/blob/master/Neural-Style/images/content3.jpeg)
![Fourth Part](https://github.com/Fahd94-sa/AI-generated-art/blob/master/Neural-Style/images/content4.jpeg)

* The applied styles are :
![First Style](https://github.com/Fahd94-sa/AI-generated-art/blob/master/Neural-Style/images/style1.jpeg)
![Second Style](https://github.com/Fahd94-sa/AI-generated-art/blob/master/Neural-Style/images/style2.jpeg)
![Third Style](https://github.com/Fahd94-sa/AI-generated-art/blob/master/Neural-Style/images/style3.jpeg)
![Fourth Style](https://github.com/Fahd94-sa/AI-generated-art/blob/master/Neural-Style/images/style4.jpeg)

* The final result is:
![Final Result](https://github.com/Fahd94-sa/AI-generated-art/blob/master/Neural-Style/output.png)

The code is based on the following tutorial:
https://pytorch.org/tutorials/advanced/neural_style_tutorial.html
