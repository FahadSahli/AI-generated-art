# Neural Style

This folder contains a joint project with [Abdullah Alsalamah](https://github.com/AbdullahAlsalamah) and Abeer Mayan (<abeermayan@gmail.com>). The project was part of the [AI Artathon](https://theglobalaisummit.com/artathon/). The Artathon aims to generate art images using AI approaches. This project uses [Neural Style](https://arxiv.org/abs/1508.06576) to generate art images by applying the style of some image (style image) to the content of another image (content image). The code is based on the following tutorial: <br>
https://pytorch.org/tutorials/advanced/neural_style_tutorial.html

Our approach is to divide the content image into 4 parts. Then, a style is applied to each part of the content image. The following are: 
* Content Image: <br>
![Content Image](https://github.com/FahadSahli/AI-generated-art/blob/master/Neural-Style/content.jpeg)

* The 4 parts of the content: <br>
<img align="middle" width="250" height="500" src="https://github.com/FahadSahli/AI-generated-art/blob/master/Neural-Style/images/content1.jpeg"> <br>
<img align="middle" width="250" height="500" src="https://github.com/FahadSahli/AI-generated-art/blob/master/Neural-Style/images/content2.jpeg"> <br>
<img align="middle" width="250" height="500" src="https://github.com/FahadSahli/AI-generated-art/blob/master/Neural-Style/images/content3.jpeg"> <br>
<img align="middle" width="250" height="500" src="https://github.com/FahadSahli/AI-generated-art/blob/master/Neural-Style/images/content4.jpeg"> <br>

* The applied styles: <br>
<img align="middle" width="250" height="500" src="https://github.com/FahadSahli/AI-generated-art/blob/master/Neural-Style/images/style1.jpeg"> <br>
<img align="middle" width="250" height="500" src="https://github.com/FahadSahli/AI-generated-art/blob/master/Neural-Style/images/style2.jpeg"> <br>
<img align="middle" width="250" height="500" src="https://github.com/FahadSahli/AI-generated-art/blob/master/Neural-Style/images/style3.jpeg"> <br>
<img align="middle" width="250" height="500" src="https://github.com/FahadSahli/AI-generated-art/blob/master/Neural-Style/images/style4.jpeg"> <br>

* The final result: <br>
![Final Result](https://github.com/FahadSahli/AI-generated-art/blob/master/Neural-Style/output.png)
