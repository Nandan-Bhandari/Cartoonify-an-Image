# Cartoonify-an-Image
It is a Python-based project in which I've used several python libraries and concepts of Machine Learning and Deep Learning. This project is mainly dependent on OpenCV library. 
Before cartoonify and saving cartoonified images, I've changed the filter of the uploaded image four times.
This project will output total six images with respect to the input image.
First one is orijinal image, which you input.
Second is GrayScale.
Third is Smooth Gray Scale image.
Fourth is Adaptive Threshold image, which transforms a grayscale image to a binary image.
Fifth is Bilateral Filter image, which can reduce unwanted noise very well while keeping edges fairly sharp. However, it is very slow compared to most filters.
Finally, Sixth is our final cartoonified image using "bitwise_and" function from OPenCV library, in brief which computes bitwise conjunction of the two arrays.
