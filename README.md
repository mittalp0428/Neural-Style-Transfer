# Neural-Style-Transfer

I used deep learning to compose one image in the style of another image.    

This is known as neural style transfer and the technique is outlined in A Neural Algorithm of Artistic Style.


Neural style transfer is an optimization technique used to take two images—a content image and a style reference image and blend them together so the output image looks like the content image, but “painted” in the style of the style reference image.


This is implemented by optimizing the output image to match the content statistics of the content image and the style statistics of the style reference image. These statistics are extracted from the images using a convolutional network.


