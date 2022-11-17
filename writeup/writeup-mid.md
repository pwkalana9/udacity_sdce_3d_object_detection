# 3D Object detection in LIDAR scans

## Section 1 : Compute Lidar Point-Cloud from Range Image

### Visualize range image channels
LIDAR data includes range measurements and reflected intensity measurements. In this activity, range channel and intensity channels of LIDAR are stacked together in one image as below.

![image](resources/range_image_stacked.png)

### Visualize LIDAR point cloud
![image](resources/pcl1.png)
![image](resources/pcl2.png)
![image](resources/pcl3.png)
![image](resources/pcl4.png)
![image](resources/pcl5.png)
![image](resources/pcl6.png)
![image](resources/pcl7.png)
![image](resources/pcl8.png)
![image](resources/pcl9.png)
![image](resources/pcl10.png)
![image](resources/pcl11.png)
![image](resources/pcl12.png)

## Section 2 : Create Birds-Eye View from Lidar PCL
### Convert sensor coordinates to BEV-map coordinates
![image](resources/bev.png)
### Compute intensity layer of the BEV map
![image](resources/bev1.png)
### Compute height layer of the BEV map
![image](resources/bev2.png)

## Section 3 : Model-based Object Detection in BEV Image
### Add a second model from a GitHub repo
### Extract 3D bounding boxes from model response
![image](resources/obj1.png)
![image](resources/obj2.png)
![image](resources/obj3.png)
![image](resources/obj4.png)
![image](resources/obj5.png)
![image](resources/obj6.png)

## Section 4 : Performance Evaluation for Object Detection
### Compute intersection-over-union between labels and detections
### Compute false-negatives and false-positives
### Compute precision and recall
![image](resources/objeval4.png)
![image](resources/objeval5.png)
![image](resources/objeval6.png)
![image](resources/objeval7.png)