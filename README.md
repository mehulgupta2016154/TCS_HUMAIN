# TCS_HUMAIN
### Git clone : https://github.com/AlexeyAB/darknet.git

### Download the following from given links

#### [initial weights YOLO](https://drive.google.com/file/d/1OBNcSfNH53HHCEZbfIRsCygDCevS8NaJ/view?usp=sharing)
#### [trained weights YOLO](https://drive.google.com/file/d/1I3JY2-0mr1wNz7ifEzxct8GJyxEy-doL/view?usp=sharing)
#### [training dataset](https://drive.google.com/file/d/1t20-WpJWvon2o7MdoS88FyBw8yYrRKln/view?usp=sharing)
#### [validation dataset](https://drive.google.com/file/d/1as5wGXC3M4ErAYn9Q0vxeLPwlS5JInNV/view?usp=sharing)


#### All other information regarding the setup can be found out in Description FILE

## Different files and their roles:
1. Cropping_Plates_from_Detection_YOLOv3_for_OCR.ipynb: Crop output objects from YOLOv3 for OCR
2. Dataset1(ANPR)_preparation_for_yolo.ipynb: preprocessing ANPR dataset as per YOLOv3 training requirements
3. (Indian_cars)_preparation_for_YOLO.ipynb: preprocessing Indian Car dataset as per YOLOv3 training requirements
4. Number_Plate_Detection_YOLOv3.ipynb: Google colab notebook for training & storing final output over test data
5. OCR_for_NumberPlate.ipynb: OCR over all cropped images and storing it in a list 
6. Description.pdf: Entire problem statement and steps to follow for executing the project
7. Train.txt,Valid.txt,obj.names,obj.data: Requirements for YOLOv3 as explained in description.pdf


### For understanding YOLOv3 training set, click [here](https://medium.com/@mehulgupta_7991/image-labelling-for-yolo-using-yolo-mark-c58eb75b77fd?source=friends_link&sk=d7957d821ed7ea33e177ad766578f63a) 
