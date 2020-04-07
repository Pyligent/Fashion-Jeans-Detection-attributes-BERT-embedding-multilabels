# fashion-jeans-detection-attributes-BERT-embedding-multilabels
### Detection, Multi-Labels Classification and Attributes Embedding

### 1. Jeans Detection and Segmentation

#### Detectron2 Model - Generalized R-CNN Models

Detectron aims to provide a high quality and industry standard codebase for object detection research. The results it has posted are incredibly accurate. The image above shows the prediction power of the software. The following object related algorithms are embedded in Detectron:
- Mask R-CNN
- RetinaNet
- Faster R-CNN
- RPN
- Fast R-CNN
- R-FCN

#### Detectron2 Archtecture

![img1](https://github.com/Pyligent/fashion-jeans-detection-attributes-BERT-embedding-multilabels/blob/master/img/detectron2.png)

#### Dataset & Annotation
 - From Jeans Websites
 - Annotation the jeans from the each images
 
#### Notebook & Results

- Detailed Training Information is in the [Notebook](https://github.com/Pyligent/fashion-jeans-detection-attributes-BERT-embedding-multilabels/blob/master/Jeans_Dectection_Segmentation_v1.ipynb)

- Reseults:   

![img2](https://github.com/Pyligent/fashion-jeans-detection-attributes-BERT-embedding-multilabels/blob/master/img/test1.png)
![img3](https://github.com/Pyligent/fashion-jeans-detection-attributes-BERT-embedding-multilabels/blob/master/img/test2.png)
![img4](https://github.com/Pyligent/fashion-jeans-detection-attributes-BERT-embedding-multilabels/blob/master/img/test3.png)
![img5](https://github.com/Pyligent/fashion-jeans-detection-attributes-BERT-embedding-multilabels/blob/master/img/test4.png)

### 2.Fashion Multi-Label Classification 

- multi-label classification and the strongly related problem of multi-output classification are variants of the classification problem where multiple labels may be assigned to each instance. Multi-label classification is a generalization of multiclass classification, which is the single-label problem of categorizing instances into precisely one of more than two classes; in the multi-label problem there is no constraint on how many of the classes the instance can be assigned to.
Formally, multi-label classification is the problem of finding a model that maps inputs x to binary vectors y (assigning a value of 0 or 1 for each element (label) in y).

- For every garment, there are a lot attributes. We can treated as the multi-labels for training and classifcation.

- Training:
  - Use fastai v1 and v2 to train the model. 
  - [Notebook(v1)](https://github.com/Pyligent/fashion-jeans-detection-attributes-BERT-embedding-multilabels/blob/master/levis_multilabel_fastaiv1.ipynb)
  - [Notebook(v2)](https://github.com/Pyligent/fashion-jeans-detection-attributes-BERT-embedding-multilabels/blob/master/multilabe_fastai2.ipynb)
  
 -Results:
 
![img6](https://github.com/Pyligent/fashion-jeans-detection-attributes-BERT-embedding-multilabels/blob/master/img/mlr1.png)
![img7](https://github.com/Pyligent/fashion-jeans-detection-attributes-BERT-embedding-multilabels/blob/master/img/mlr2.png)
![img8](https://github.com/Pyligent/fashion-jeans-detection-attributes-BERT-embedding-multilabels/blob/master/img/mlr3.png)

