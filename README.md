
# Using CNN for Disease Classification
## Citing
If you find this code useful, then consider referring to the [paper](https://github.com/BALAVIDULA/plant_disease_detection/blob/main/Research%20Paper.docx);
## Dataset
We have used publicly available Corn or Maize Leaf Disease Dataset from Kaggle.

This consists of 4 directories:
- Blight
* Common_Rust
+ Gray_Leaf_Spot
- Healthy

The dataset used can be downloaded from [here]( https://www.kaggle.com/datasets/smaranjitghose/corn-or-maize-leaf-disease-dataset).
## Abstract
Deep Learning has been highly successful in replacing the traditional mechanisms. Traditionally, farmers identify the disease present in plants with their domain knowledge and experience. But misclassifying of diseases and neglection causes the plants to rot.  Hence, this problem is addressed by detecting the types of diseases in corn plants by just classifying the starting stage of diseases from the leaves. We have used VGG16 architecture as the backbone of the model. For evaluation, we used accuracy metrics that obtained an accuracy of 0.75.
## Environment and tools
1. Colab Notebook
2. Numpy
3. Tensorflow
4. CV2
5. Matplotlib
6. Keras
## Results
Visualization of Dimensions of an Image

![download1](https://user-images.githubusercontent.com/114278846/210065579-26951288-7572-4627-9dd1-d8e2644113c0.png)

Visualization of Feature Maps
> Convo2d Layer

![download2](https://user-images.githubusercontent.com/114278846/210065865-c4eec8ab-6913-497e-b7ef-e16e3cd14eab.png)

> Maxpooling Layer

![download3](https://user-images.githubusercontent.com/114278846/210065907-8493557b-4a3b-4f6d-b5b1-6fe4357ebf2a.png)


