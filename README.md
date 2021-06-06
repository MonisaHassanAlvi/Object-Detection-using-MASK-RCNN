# Object-Detection-using-MASK-RCNN
A console based python project for object detection using MASK-RCNN with transfer learning. 

# Tools & Applications
- Pycharm
- Labellimg Annotation Software
- Coco Pretrained Weights

# Description
We have two types of identity cards, and each card has many fields. We have to extract “first name”, “last name” “card number”, “date of birth”, “address”, “country/state/province”. We have taken 4 types of cards: e.g,  (i) Pakistan CNIC, (ii) UK Passport, (iii) Pakistani Passport,  (iv) UK driving license.

# Dataset
We have download these both type of cards from google images. We have downloaded 25 for each.

# Annotations
We have used labellimg annotation software to annotate our images.

# Augmentation
After annotations, we have used an augmentation technique to create more images. we have rotated an image at every 4 degree and in this way we have created 90 images from one image.

# Transfer Learning
We have trained the model on our own dataset. Basically we have used transfer learning and for that we have used the coco pretrained weights and have used ResNet50.

# Output
![image](https://user-images.githubusercontent.com/85407775/120935322-9d2dc900-c71b-11eb-8f94-99b0d342a73d.png)
