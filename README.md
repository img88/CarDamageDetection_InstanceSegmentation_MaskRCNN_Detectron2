
# Car Damage Detection using Detectron2

Detect damaged car parts using instance segmentation, mask r-cnn, and the Detectron2 library.

Using the kaggle dataset by LPLENKA, there are 59 images for training, 11 for validation, and 8 images for testing


![Car Damage Detection Mask RCNN Detectron2](./img/output.png?raw=true "Car Damage Detection Mask RCNN Detectron2")


## How to Run

- Kaggle: Go to [COCO Car Damage Dataset by LPLENKA](https://www.kaggle.com/datasets/lplenka/coco-car-damage-detection-dataset), create code with that dataset and import the kaggle notebook.
- Google Colab: [Create your Kaggle API Token](https://www.kaggle.com/general/74235), upload this notebook to google colab, and dont forget to upload your API Token in the notebook.
## About Detectron2

Detectron2 is Facebook AI Research's next generation library that provides state-of-the-art detection and segmentation algorithms. It is the successor of Detectron and maskrcnn-benchmark. It supports a number of computer vision research projects and production applications in Facebook.
## About Dataset

**Context**

The dataset contains car images with one or more damaged parts. The img/ folder has all 80 images in the dataset. There are three more folders train/, val/ and test/ for training, validation and testing purposes respectively.

**Folders**

**train/:**

Contains 59 images.

COCO_train_annos.json: Train annotation file for damages where damage is the one and only category.
COCO_mul_train_annos.json: Train annotation file for parts having damages. There are five categories of parts based on which part the damage has happened. The parts can be namely, headlamp, front_bumper, hood, door, rear_bumper.

**val/:**

Contains 11 images.

COCO_val_annos.json: Validation annotation file for damages where damage is the one and only category.
COCO_mul_val_annos.json: Validation annotation file for parts having damages. There are five categories of parts based on which part the damage has happened. The parts can be namely, headlamp, front_bumper, hood, door, rear_bumper.

**test/:**

Contains 8 images.

**Annotation files have the following keys:**

"annotations": Contains the bounding box and segmentation array.
"categories": Contains the list of categories in the annotation.
"images": Details of each image used in the annotation.
"info": Creator information
"licenses": License information
## Acknowledgements

 - [Detectron2 Getting Started Notebook](https://colab.research.google.com/drive/16jcaJoc6bCFAQ96jDe2HwtXj7BMD_-m5)
 - [COCO Car Damage Dataset by LPLENKA](https://www.kaggle.com/datasets/lplenka/coco-car-damage-detection-dataset)


## Authors

- [@img88](https://github.com/img88)

