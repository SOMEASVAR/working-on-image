# Name : R.SOMEASVAR
# Resgister number : 212221230103
# Working-on-images
# Question:
```
To work some image conversion operations on a image.
```
# Program:
```
#Original image
import cv2
img=cv2.imread('car.jpg',1)
cv2.imshow('original image',img)
cv2.waitKey(0)
cv2.destroyAllWindows()


#Gray scale image
gray=cv2.cvtColor(img,cv2.COLOR_BGR2GRAY)
cv2.imshow('Gray scale image',gray)
cv2.waitKey(0)
cv2.destroyAllWindows()


#HSV image
hsv_image=cv2.cvtColor(img,cv2.COLOR_BGR2HSV)
cv2.imshow('HSV image',hsv_image)
cv2.waitKey(0)
cv2.destroyAllWindows()


#Display H,S and V
h,s,v=cv2.split(hsv_image)
cv2.imshow('H',h)
cv2.imshow('S',s)
cv2.imshow('V',v)
cv2.waitKey(0)
cv2.destroyAllWindows()
```
# OUTPUT:
![1](https://user-images.githubusercontent.com/93434149/176348699-e738310d-5ce8-4a4c-a80c-8858dcd7e733.jpg)
![2](https://user-images.githubusercontent.com/93434149/176348709-adac414b-c487-4308-bfab-019c791f8b16.jpg)
![3](https://user-images.githubusercontent.com/93434149/176348770-68528886-9860-4168-9a7a-5a3825ff1f60.jpg)
