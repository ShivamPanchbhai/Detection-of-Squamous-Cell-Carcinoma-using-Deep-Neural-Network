# Detection-of-Squamous-Cell-Carcinoma-using-Deep-Neural-Network

The oral cavity dataset that we used for this project is available on this link->
https://github.com/Tabassum2019/A-histopathological-image-repository-of-normal-epithelium-of-Oral-Cavity-and-OSCC/blob/master/README.md
we have only used the 100x first set of the oral cavity Histopathological images. In the first set there are 89 Normal images and 438 OSCC images.
The first task that we did was split the First set into train folder and validation folder.
So now the train set has 89 normal images and 438 OSCC images.
To correct this imbalance, we used data augmentation on 3 parameters on the train folder of the normal images.
1)	Random rotation (between 25% to the left and 25% to the right)
2)	Random noise
3)	Horizontal Flip

Now, After Augmenting 89 Normal Images to 349
Total 349+89 = 438 Normal Images in the train folder. Now we have 438 Normal images and 438 OSCC images in the train set. The problem of data imbalance is resolved.
Optimiser used: RMSProp. 
