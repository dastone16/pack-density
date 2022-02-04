# pack-density
Image analysis of pack density

Input of a image of can pack from above.

Circles are placed on can domes.

Possible adjustements are:
r_a which adds pixels slightly larger on each can.  Alogrithm tends to under size can edge.
HoughCircles: minRadius and maxRadius
these radius can be optimized by looking at output array

Utilizes cv2 library
Google colab requires slight adjustment to show image to cv2_imshow

Outputs jpg with circle annotations
Pack density is calculated and appended on image
Output file has time/date in "%Y%m%d-%H%M" form
