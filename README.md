# Void-Hack-Web-App
##Our solution
We are taking two images as our input.A **content image** and a **style-image**.We then wish to create a mixed image which has contours of the content image and colours and texture of the styled-image.

##About this process
-we want contour lines from content image
-we want textures from style image
-we identify the features that exist for classification
-process is to minimize the loss between labeled imageand feature map output
-each filter performs operation on input
-starts with random noise for mixed image
-calculation of loss functions at different layers and then weigh of these loss functions at different layers are done
-gradient of combined loss functions to update mixed image

##Image Segmentation
Image segmentation is done in order to get ROI(i.e region of interest) in potrait images where we want to apply style.
###Mask R-CNN
