# Neural-Style-Transfer-In-Pytorch
## Personal Project
 Based on the paper A Neural Algorithm of Artistic Style, I implemented it in the Pytorch environment.
 
![st ani](https://user-images.githubusercontent.com/104747868/215529807-dcb1af4a-2037-4651-aba7-ad0bf535ed55.gif)

+ [A Neural Algorithm of Artistic Style](https://arxiv.org/pdf/1508.06576.pdf) & [논문 리뷰 포스팅 개인 블로그](https://westchaevi.tistory.com/4)
+ Concept of VGGNet 
+ Applying Transformation
+ Defining Loss function & Optimizer
-------------------------------------------------------------------------------------------------

#### Review
[Neural Style Transfer code](https://github.com/WestChaeVI/Neural-Style-Transfer-In-Pytorch/blob/main/Neural_Style_Transfer_For_Pytorch.ipynb) 
> ![st git](https://user-images.githubusercontent.com/104747868/215530005-813c4910-7979-491b-8844-9da5690efb26.jpg)

> Proceed with Google Colab
>
> Bring the Vgg19 model, which is a pretrained model, to the Convolution layer and apply weights to the input_image.
>
> As you can see in the Output, the higher the epoch, the stronger the style features are applied.
>
> Recommend : If you add fine tuning, you will get even better results.
>
> Note : Input_image should preferably be a picture in rgb channel, not cmyk.
