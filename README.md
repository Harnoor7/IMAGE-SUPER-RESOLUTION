# IMAGE-SUPER-RESOLUTION
An image super-resolution convolutional neural network model to enhance image quality.

<b>The trained model showed great results achieving a very high PSNR value (performance metric to evaluate the image quality) of 39 which is better than the traditional methods.</b>

Single image super-resolution (SR), which aims at recovering a high-resolution image from a single low-resolution image, is a classical problem in computer vision.
We consider a convolutional neural network that directly learns an end-to-end mapping between low- and high-resolution images. <br /> 
The network directly learns an end-to-end mapping between low and high-resolutionimages, with little pre/postprocessing beyond the optimization. 
PSNR value of SRCNN is improved the SRCNN by introducing larger filter size in the non-linear mapping layer, and explore deeper structures by adding nonlinear mapping layers.

Approach primarily consists of three operations:

1. Patch extraction and representation
2. Non-linear mapping
3. Reconstruction

which can be pictorially shown as : <br/>

 <img src="https://github.com/Harnoor7/IMAGE-SUPER-RESOLUTION/blob/master/Videos/approach.png">
<br/>

RESULTS
| Input      | Output      |
|------------|-------------|
| <img src="https://github.com/Harnoor7/IMAGE-SUPER-RESOLUTION/blob/master/Videos/input.png" width="250"> | <img src="https://github.com/Harnoor7/IMAGE-SUPER-RESOLUTION/blob/master/Videos/output.png" width="250"> | <br/>
| <img src="https://github.com/Harnoor7/IMAGE-SUPER-RESOLUTION/blob/master/Videos/input1.png" width="250"> | <img src="https://github.com/Harnoor7/IMAGE-SUPER-RESOLUTION/blob/master/Videos/ouput1.png" width="250"> |

