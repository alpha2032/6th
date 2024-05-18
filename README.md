import cv2
from matplotlib import pyplot as plt
image=cv2.imread("butterfly_2.jpeg",1)
cv2.imshow("input", image)
histogram=cv2.calchist([image],[0], None, [256], [0,256])
plt.plot(histogram,color="c")
plt.show()
