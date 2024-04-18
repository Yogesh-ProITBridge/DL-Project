# Computer vision-Project

Problem Statement : 

This dataset was downloaded from the NEU Metal Surface Defects Database, which collects four kinds of
typical surface defects of metal strips: Crack, Pinhole, undercut, shrinkage. 
The database includes 1040 images and 199 samples, each of four typical surface defects.
Sample image files are uploaded with an name of cracks, pin hole, shrinkage, undercut.

I'm Using YOLO V5 from Ultraytics
Yolov5 link - https://github.com/ultralytics/yolov5
Yolov6 link - https://github.com/meituan/YOLOv6

Training time of V5 model with T4 GPU
- CPU times: user 18 s, sys: 2.18 s, total: 20.2 s
- Wall time: 43min 35s
  
Training time of V6 model with T4 GPU
-CPU times: user 13.6 s, sys: 1.58 s, total: 15.2 s
-Wall time: 30min 38s

I also attached my .ipynb file (Metal_Detection) where you can able to see the cloning steps of Yolo

Steps :
- Data Agumentation
- Data Annotation
- Split the labels and images into train and validation
- Choose the model to train
- Testing the model
  
