# varshithiplab
Develop a program to perform linear transformation on a image.

Description: Here in the codes, we have used the getRotationMatrix function to define the parameter required in the warpAffine function to tell the function to make a matrix that can give a required rotation angle.

The warpAffine() function applies an affine transformation to the image. After applying affine transformation, all the parallel lines in the original image will remain parallel in the output image as well.
import cv2

image = cv2.imread('img1.jpg')

height, width = image.shape[:2]

center = (width/2, height/2)

rotate_matrix = cv2.getRotationMatrix2D(center=center, angle=180, scale=1)

rotated_image = cv2.warpAffine(src=image, M=rotate_matrix, dsize=(width, height))

cv2.imshow('Original image', image)

cv2.imshow('Rotated image', rotated_image)

cv2.waitKey(0)

cv2.imwrite('rotated_image.jpg', rotated_image)
