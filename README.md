# Vehicle-Number-Plate-Recognition

This project is divided into two parts.

In first part, we first train the yolo for recognising the number plates in an image.
https://towardsdatascience.com/tutorial-build-an-object-detection-system-using-yolo-9a930513643a
The data required was prepared using this tutorial.
https://mozanunal.com/2019/08/yoloColabDemo/
This tutorial can be refered for running yolo on Google colab.
To perform transfer learning, darknet model is used and pretrained weights for yolov3 are used.
After training, the final weights were stored in drive.

In second part, the trained weights from first part is used to recognise number plates in an image using opencv, and bounding boxes arre created. Then OCR is performed on cropped image to get vehicle number and web-scraping is done to extract the data of vehicle related to that particular vehicle number.
Final trained weights can be obtained at https://drive.google.com/file/d/1I3JY2-0mr1wNz7ifEzxct8GJyxEy-doL/view
