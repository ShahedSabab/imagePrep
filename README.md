# imagePrep
The objective of this project is to prepare images for the segmentation tasks. This can be used as an immediate image pre-processing step for vision models such as [SDD-Net]: https://www.researchgate.net/publication/336358391_SDDNet_Real-time_Crack_Segmentation and [U-Net]: https://arxiv.org/abs/1505.04597. There are 3 pre-processing   

The objective is to crop an image automatically given specific dimension. This can be used to preprocess training images for vision problem e.g., preprocess masked and unmasked images for segmentation task. 

# How to run:
1. Install the opencv for python.

> pip install opencv-python

2. Create 3 directories to store the training images. 

> masked_image

> unmasked_image

> cropped_image

3. Copy the original images to the unmasked_image directory and masked images to the masked_image directory.

4. Open the crop.py and set the file_num variable with the intended file number, which you want to crop. (For IMG13: just set the value as 13)

5. For other modifications, you can also change the intended height & width, and pixel density. 

6. Run the crop.py

7. Check the cropped_image directory for the cropped images.

