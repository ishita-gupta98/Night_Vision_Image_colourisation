# Night Vision Image colourisation
Computer Vision project POSTECH, Korea 2019

This project proposes two methods for colorizing
night vision images to compare the accuracy of
object detection. 
In the first method we use Lab coefficients along with Encoder-Decoder architecture and in the second we use GAN network based on MITs DeOldify architecture. 
Our aim was to increase the object detection accuracy of night vision images by colourising the images. 

After our experimental analysis,
we found that colorization did not bring much
change to the accuracy of object detection. We give
analysis conclusions based on different methods. In
the first method, because we used the L value of
the night vision image, the L value of the night
vision image is black or dark in a large range, and
because the L value has not been processed, our
colorization effect is not ideal. In the second
method we deal with this problem and give
acceptable colorization effects. However, because
the resolution of the image itself is too low, the
effect of colorization is not ideal, too. Based on our
current experiments, we find that colorized images
do not give significant improvements in object
detection results. We give the future development
direction of this project, which is to improve the
resolution of the image to increase the coloring
effect to a greater extent.

For information regarding results, dataset and methodology please refer to the paper or mail ishita.gupta0810@gmail.com
