<h1 align="center"> Utilizing different GANs to re-generate the clothes colour  </h1>

<h2>CycleGAN</h2>

We are using CycleGAN to generate the image of the same person with a different colour of the shirt/t-shirt.   
The training set consists of two different identities from the Market-1501 dataset. 

<h3>For red to green</h3>
Domain-A - ID_1 - green   

Domain-B - ID_2 - Maroon   

Input image from the domain A and it's domain B output.   
![](https://github.com/Dipeshtamboli/GAN_for_clothes/blob/master/CycleGAN/output_old/A/0005_in.jpg)
![](https://github.com/Dipeshtamboli/GAN_for_clothes/blob/master/CycleGAN/output_old/A/0005.png)
![](https://github.com/Dipeshtamboli/GAN_for_clothes/blob/master/CycleGAN/output_old/A/0004_in.jpg)
![](https://github.com/Dipeshtamboli/GAN_for_clothes/blob/master/CycleGAN/output_old/A/0004.png)
![](https://github.com/Dipeshtamboli/GAN_for_clothes/blob/master/CycleGAN/output_old/A/0003_in.jpg)
![](https://github.com/Dipeshtamboli/GAN_for_clothes/blob/master/CycleGAN/output_old/A/0003.png)
![](https://github.com/Dipeshtamboli/GAN_for_clothes/blob/master/CycleGAN/output_old/A/0002_in.jpg)
![](https://github.com/Dipeshtamboli/GAN_for_clothes/blob/master/CycleGAN/output_old/A/0002.png)
![](https://github.com/Dipeshtamboli/GAN_for_clothes/blob/master/CycleGAN/output_old/A/0001_in.jpg)
![](https://github.com/Dipeshtamboli/GAN_for_clothes/blob/master/CycleGAN/output_old/A/0001.png)


Input image from the domain B and it's domain A output.   
![](https://github.com/Dipeshtamboli/GAN_for_clothes/blob/master/CycleGAN/output_old/B/0005_in.jpg)
![](https://github.com/Dipeshtamboli/GAN_for_clothes/blob/master/CycleGAN/output_old/B/0005.png)
![](https://github.com/Dipeshtamboli/GAN_for_clothes/blob/master/CycleGAN/output_old/B/0004_in.jpg)
![](https://github.com/Dipeshtamboli/GAN_for_clothes/blob/master/CycleGAN/output_old/B/0004.png)
![](https://github.com/Dipeshtamboli/GAN_for_clothes/blob/master/CycleGAN/output_old/B/0003_in.jpg)
![](https://github.com/Dipeshtamboli/GAN_for_clothes/blob/master/CycleGAN/output_old/B/0003.png)
![](https://github.com/Dipeshtamboli/GAN_for_clothes/blob/master/CycleGAN/output_old/B/0002_in.jpg)
![](https://github.com/Dipeshtamboli/GAN_for_clothes/blob/master/CycleGAN/output_old/B/0002.png)
![](https://github.com/Dipeshtamboli/GAN_for_clothes/blob/master/CycleGAN/output_old/B/0001_in.jpg)
![](https://github.com/Dipeshtamboli/GAN_for_clothes/blob/master/CycleGAN/output_old/B/0001.png)

<h3>For black to non-black clothes</h3>
Domain-A - Several Ids - black

Domain-B - Several Ids - non-black   

Input image consisting of black shirt/t-shirt to non-black shirt/t-shirt output.   
![](https://github.com/Dipeshtamboli/GAN_for_clothes/blob/master/CycleGAN/output_v1/B/0001_in.jpg)
![](https://github.com/Dipeshtamboli/GAN_for_clothes/blob/master/CycleGAN/output_v1/B/0001_out.png)
![](https://github.com/Dipeshtamboli/GAN_for_clothes/blob/master/CycleGAN/output_v1/B/0002_in.jpg)
![](https://github.com/Dipeshtamboli/GAN_for_clothes/blob/master/CycleGAN/output_v1/B/0002_out.png)
![](https://github.com/Dipeshtamboli/GAN_for_clothes/blob/master/CycleGAN/output_v1/B/0003_in.jpg)
![](https://github.com/Dipeshtamboli/GAN_for_clothes/blob/master/CycleGAN/output_v1/B/0003_out.png)
![](https://github.com/Dipeshtamboli/GAN_for_clothes/blob/master/CycleGAN/output_v1/B/0004_in.jpg)
![](https://github.com/Dipeshtamboli/GAN_for_clothes/blob/master/CycleGAN/output_v1/B/0004_out.png)
![](https://github.com/Dipeshtamboli/GAN_for_clothes/blob/master/CycleGAN/output_v1/B/0005_in.jpg)
![](https://github.com/Dipeshtamboli/GAN_for_clothes/blob/master/CycleGAN/output_v1/B/0005_out.png)

Also from non-black to black.   
![](https://github.com/Dipeshtamboli/GAN_for_clothes/blob/master/CycleGAN/output_v1/A/0001_in.jpg)
![](https://github.com/Dipeshtamboli/GAN_for_clothes/blob/master/CycleGAN/output_v1/A/0001_out.png)
![](https://github.com/Dipeshtamboli/GAN_for_clothes/blob/master/CycleGAN/output_v1/A/0002_in.jpg)
![](https://github.com/Dipeshtamboli/GAN_for_clothes/blob/master/CycleGAN/output_v1/A/0002_out.png)
![](https://github.com/Dipeshtamboli/GAN_for_clothes/blob/master/CycleGAN/output_v1/A/0003_in.jpg)
![](https://github.com/Dipeshtamboli/GAN_for_clothes/blob/master/CycleGAN/output_v1/A/0003_out.png)
![](https://github.com/Dipeshtamboli/GAN_for_clothes/blob/master/CycleGAN/output_v1/A/0004_in.jpg)
![](https://github.com/Dipeshtamboli/GAN_for_clothes/blob/master/CycleGAN/output_v1/A/0004_out.png)
![](https://github.com/Dipeshtamboli/GAN_for_clothes/blob/master/CycleGAN/output_v1/A/0005_in.jpg)
![](https://github.com/Dipeshtamboli/GAN_for_clothes/blob/master/CycleGAN/output_v1/A/0005_out.png)
![](https://github.com/Dipeshtamboli/GAN_for_clothes/blob/master/CycleGAN/output_v1/A/0006_in.jpg)
![](https://github.com/Dipeshtamboli/GAN_for_clothes/blob/master/CycleGAN/output_v1/A/0006_out.png)
![](https://github.com/Dipeshtamboli/GAN_for_clothes/blob/master/CycleGAN/output_v1/A/0007_in.jpg)
![](https://github.com/Dipeshtamboli/GAN_for_clothes/blob/master/CycleGAN/output_v1/A/0007_out.png)
![](https://github.com/Dipeshtamboli/GAN_for_clothes/blob/master/CycleGAN/output_v1/A/0008_in.jpg)
![](https://github.com/Dipeshtamboli/GAN_for_clothes/blob/master/CycleGAN/output_v1/A/0008_out.png)
![](https://github.com/Dipeshtamboli/GAN_for_clothes/blob/master/CycleGAN/output_v1/A/0009_in.jpg)
![](https://github.com/Dipeshtamboli/GAN_for_clothes/blob/master/CycleGAN/output_v1/A/0009_out.png)
![](https://github.com/Dipeshtamboli/GAN_for_clothes/blob/master/CycleGAN/output_v1/A/0010_in.jpg)
![](https://github.com/Dipeshtamboli/GAN_for_clothes/blob/master/CycleGAN/output_v1/A/0010_out.png)