# Data Augmentation

Because a CNIC is a very valuable asset, getting its data is an extremely hard job. 

And hence, to solve this problem, we have created this pipeline which augments images of CNICS. Data Augmentation will help us in recreating different real life scenarios by merely a couple of images.

# Augmentations applied

## 1. JPEG Compression
JPEG compression attempts to create patterns in the color values in order to reduce the amount of data that needs to be recorded, thereby reducing the file size. In order to create these patterns, some color values are approximated to match those of nearby pixels.

It mimics a lower quality image, if taken from a low end camera.

![](images/before.png) --> ![](images/jpegcomp_after.jpg)

## 2. Gausian Blur
In image processing, a Gaussian blur (also known as Gaussian smoothing) is the result of blurring an image by a Gaussian function. It is a widely used effect in graphics software, typically to reduce image noise and reduce detail.

It smoothens an image, hence, making the card cuts less visible.

![](images/before.png) --> ![](images/gausblur_after.png)

## 3. Gausian Noise
The reason why a Gaussian makes sense is because noise is often the result of summing a large number of different and independent factors.

![](images/before.png) --> ![](images/gausnoise_after.png)

## 4. Speckle Noise
Speckle is a granular interference that inherently exists in and degrades the quality of the active radar, synthetic aperture radar (SAR), medical ultrasound and optical coherence tomography images.

Gives the images a very constarsty feel, mimicing a focused shot.

![](images/before.png) --> ![](images/speckle.png)

## 5. SnP Noise
Mimics a worn out CNIC.

![](images/before.png) --> ![](images/snp.png)

## 6. Poison Noise
Mimics a worn out CNIC and a bad quality image.

![](images/before.png) --> ![](images/poison.png)

## 7. Brightness
Adjusts the brighteness of the images to different extents.

![](images/before.png) --> ![](images/brightness.png)

## 8. Contrast
Mimics a high quality camera's image.

![](images/before.png) --> ![](images/contrast.png)

## 9. Zoom
People cannot hold CNICs in the exact position as to what they will be told, hence, this augmentation tries to mimic that.

![](images/before.png) --> ![](images/zoom.png)

## 10. Rotation
People cannot hold CNICs in the exact orientation as to what they will be told, hence, this augmentation tries to mimic that.

![](images/before.png) --> ![](images/rotation.png)

## 11. Erosion
Tries to mimic worn out and old CNICs.

![](images/before.png) --> ![](images/erosion.png)

## 12. Sharpening
Increases the sharpness of the image, hence mimicing a high quality focused image.

![](images/before.png) --> ![](images/sharp.png)
