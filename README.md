# Classification-on-Logo-2K-Dataset-using-YOLOv9
"Logo-2K+" is a large-scale logo dataset with a diverse range of logo classes from real-world logo images containing 167,140 images with 10 root categories and 2,341 categories. In this work, we apply the newly released YOLOv9 for logo classification purposes in the "Logo-2K+" dataset.

# Custom Model Architecture for YOLOv9 for classification purposes
YOLOv9 do not have the classification module yet. In this work, we modified the object detection module of YOLOv9 for classfication purpose. The modifed model is the 'yolov9c-cls.yaml' file which needs to be imported in the model while training.
