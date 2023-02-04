# CEP Project, Satellite Image Processing

This is a project i recieved in my 5th Semester at the University. It deals with image processing, specifically processing and analyzing satellite images(Landstat).

- Firstly we analyze the bands of the orignal satellite image and then merge them into a single image using earthpy library to form a colored image from all the bands. Then we apply basic operations on the image such as scaling the image.

- In the next part we apply Principle Component Analysis on the multispectral image, the PCA function that is to be used was hand coded rather than using PCA through a library.

- Lastly we check the error of the PCA applied image against the orignal multispectral image using the coded mean squared error function.
