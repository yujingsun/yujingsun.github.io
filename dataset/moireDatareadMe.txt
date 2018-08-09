Moire Photo Benchmark

---------------------------------------------------------------------------------------------------------------
Please cite the following paper if you use this dataset:
Sun, Yujing, Yizhou Yu, and Wenping Wang. "Moiré Photo Restoration Using Multiresolution Convolutional Neural Networks." 
IEEE Transactions on Image Processing 27.8 (2018): 4160-4172.
---------------------------------------------------------------------------------------------------------------

<1. Summary>
The uncontaminated reference images in our benchmark come from the validation images and testing images of 
ImageNet ISVRC 2012 dataset. (http://www.image-net.org/challenges/LSVRC/2012/)

Of all the pairs of images, 90% is used as the traning data and 10% is used for validation and testing. 
The images in folder source and folder target are registered as we stated in the paper.


<2. Image Naming>
Images in this benchmark are named as image_class_partX_Y_type.png

class: test/val (test and val means that this image is from the testing and validation image of ImageNet ISVRC 2012,respectively.)
X: 001-011 for class test and 001-010 for class val 
Y: the index of this image
type: source/target (source means this is a contaminated image and target means this is a clean reference image.)

<3. Capture Device Specifications>
Phone Models：
(1)iphone6
(2) Samsung Galaxy S7 Edge
(3) Sony Xperia Z5 Premium Dual

Display Monitors：
(1) Dell U2410 1920
(2) DELL SE198WFP 1280
(3) Macbook Pro Retina (Mid 2014) 2560

phoneMode (1) and Display Monitor(1): val_part001, val_part002, val_part007
phoneMode (1) and Display Monitor(2): val_part003, val_part004, val_part008
phoneMode (1) and Display Monitor(3): test_part001, val_part010

phoneMode (2) and Display Monitor(1): test_part003, test_part008
phoneMode (2) and Display Monitor(2): test_part002, test_part007
phoneMode (2) and Display Monitor(3): val_part005, val_part006, val_part009

phoneMode (3) and Display Monitor(1): test_part004, test_part009
phoneMode (3) and Display Monitor(2): test_part005, test_part010
phoneMode (3) and Display Monitor(3): test_part006, test_part011