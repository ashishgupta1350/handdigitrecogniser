# handdigitrecogniser
Keras trained model for hand digit recognition using custom data.



### Lets see the way to go about it!
1) Generate training images using camera and saving them, get like 50 images of various tilts and angles and various magnifications all of size 72 by 72 ( So that we can scale down on demand )

2) Apply filters and generate 5 images per image to generate 250 images per class.

3) Generate a csv file for the images stored as numbers

4) Generate csv file for labels.
