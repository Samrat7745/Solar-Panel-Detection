# Solar-Panel-Detection
Detecting Solar Panels from Satellite images using YOLOv8

## Remember to change the directory location

## Since the data limit exceeded. I can't upload the data file

# Steps to begin data processing

* Create a folder named dataset in the root folder
* Create a folder named data in the root folder
* Download the dataset from https://drive.google.com/drive/folders/13QfMQ-7OdWKw-LR8DmypKwSHtI0Hk2wh?usp=sharing
* place the dataset in the "dataset" folder
* create "images" and "labels" folder in data folder
* Inside "images" and "labels" add "test","train" and "val" folders in both the folders
* change values of hd_folder_path and native_folder_path in the Task1-2.ipynb file to "\<path to the Solar-Panel-detection folder>/dataset/\<labels_hd or labels_native >"
* Change the value of root directory in data.yaml file in data/ folder to "\<path to the Solar-Panel_detection folder>"
Run the script
