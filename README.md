# Void-Hack-Web-App
## Our solution
We are taking two images as our input.A **content image** and a **style-image**.We then wish to create a mixed image which has contours of the content image and colours and texture of the styled-image.

## About this process
<ul>
  <li>we want contour lines from content image</li>
<li>we want textures from style image</li>
<li>we identify the features that exist for classification</li>
<li>process is to minimize the loss between labeled imageand feature map output</li>
<li>each filter performs operation on input</li>
<li>starts with random noise for mixed image</li>
<li>calculation of loss functions at different layers and then weigh of these loss functions at different layers are done</li>
<li>gradient of combined loss functions to update mixed image</li>
  </ul>

## Image Segmentation
Image segmentation is done in order to get ROI(i.e region of interest) in potrait images where we want to apply style.
### Mask R-CNN
