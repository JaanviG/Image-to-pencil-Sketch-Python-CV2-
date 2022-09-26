# Image-to-pencil-Sketch-Python-CV2

Reading the image in RGB format and converting it to a grayscale image using CV2 library from python, matplotlib, style cvtcolor, bitwise_not, Gaussian_Blur and divide and converting the image.
# Problem Statement:-
* We need to read the image in RBG format and then convert it to a grayscale image. This will turn an image into a classic black and white photo.
Then the next thing to do is invert the grayscale image also called negative image, this will be our inverted grayscale image. Inversion can be used to enhance details. * Then we can finally create the pencil sketch by mixing the grayscale image with the inverted blurry image.
* This can be done by dividing the grayscale image by the inverted blurry image. Since images are just arrays, we can easily do this programmatically using the divide function from the cv2 library in Python.

![image](https://user-images.githubusercontent.com/112110549/192283663-6051f8d8-c5c7-463f-94e7-2f3dd224deb8.png)

Imported original Image

![image](https://user-images.githubusercontent.com/112110549/192283851-35b3c883-2261-4ed7-a1dd-f6d677a617a9.png)

Grayscale image by using cvtcolor

![image](https://user-images.githubusercontent.com/112110549/192284042-373a9c7d-a552-4aab-83e8-5fb9e325d563.png)

Inverted image by using bitwise

![image](https://user-images.githubusercontent.com/112110549/192284183-a511b5e5-aabb-47bd-b809-2581bbbc681b.png)

Smoothen image by using Gaussian_Blur

![image](https://user-images.githubusercontent.com/112110549/192284338-943e90cf-3043-4115-95ea-0c82f392d45e.png)

Final output skechted Image
