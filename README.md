# CANNY-EDGE-DETECTION
## AIM : 
To implement the canny edge detection using python program.
## PROGRAM :
```
NAME : NITHYA D
REGISTER NUMBER : 212223240013
```
```
import cv2
import matplotlib.pyplot as plt
img = cv2.imread('Nithya.jpg',cv2.IMREAD_GRAYSCALE)
blurred =cv2.GaussianBlur(img, (5,5),0)
edges = cv2.Canny(blurred, 50, 150) 
plt.figure(figsize=(10,5))
plt.subplot(121),plt.imshow(img, cmap='gray')
plt.title('Original Image'), plt.axis('off')
plt.subplot(122),plt.imshow(edges, cmap='gray')
plt.title('Detected Edges'), plt.axis('off')
plt.show()
```
## OUTPUT :
<img width="924" height="530" alt="image" src="https://github.com/user-attachments/assets/377c4470-f1ef-4d2c-9513-872cebb4f4e1" />

## RESULT :
Thus the program to implement the canny edge detection was executed successfully.

