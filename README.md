# Advanced
In this project, first I Clone yolov5 repository : https://github.com/ultralytics/yolov5.git

Then I config in file utils.dataloders.py , I add 1 parametor is frame ( to define parameter FramID )
![image](https://github.com/RyanPham19092002/Advanced/assets/122810752/7ed8f35e-9520-4afb-9b00-9dada15308bc)

After that, I take this parameter and set it with name "frameID" in file detect.py
![image](https://github.com/RyanPham19092002/Advanced/assets/122810752/f3e14de7-a551-45d2-8ab3-4877c2b1f5fa)

In this current file, I generate variable "obj_dict" to save the information about (FrameID, Object’s class, Object’s bounding box, Confidence) of object and then save into a JSON file.
![image](https://github.com/RyanPham19092002/Advanced/assets/122810752/27f1757b-a4b5-4d84-a6f5-c2fac4bb50c2)
As you see in this picture, I take information of bouding box, confidence score and class in "det", save it to each variable , and then save it into a "detections.json" file

Additionally, this is the googledrive link : https://drive.google.com/drive/folders/1nDf7pkot72yT4gKh633G8E9ycgO4ShN_?usp=sharing
of video result after we use YOLOv5 model with "yolov5s.pt" weights and confidence is 0.4
![image](https://github.com/RyanPham19092002/Advanced/assets/122810752/a675df0e-25d3-49b4-b83f-f7c1b3bdd3cf)
