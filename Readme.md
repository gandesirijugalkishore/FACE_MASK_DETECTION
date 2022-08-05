## JUGAL KISHORE GANDHESIRI
###  A04228048

## Readme File For Face Mask Detection:
## This project is implemented in Python using Keras, Tensorflow and OpenCV.


Requirements:
## python,Jupyter Notebook, opencv python,Keras==2.1.5,tensorflow==2.2.0,numpy,scikit learn,matplotlib.



File Insights:
1. There are three different jupyter notebooks involved for data processing , training and testing the model.
 
Dataset and Model:
1. Dataset folder which includes two sub folders i.e with_mask and without_mask.

2. Apart from this haarcascade_frontalface_default.xml  which is the classifier for detection of facial features.

3. model-017.model which is the pretrained model can be found in the below link.[This is just included as it could be used directly for execution of the file without training the models]. 

https://drive.google.com/drive/folders/13GKwTNKAjxXi8UKyLFtdAKM-fkSCXsxP?usp=sharing

Steps to Be followed for a Succesfull Execution of the Project:

1. Before execution of notebooks please make sure the data and the models are downloaded and included in the the root directory of the project.

2. Open the First notebook i.e data preprocessing notebook. Which includes loading the dataset.The path for the dataset should be absoulte,although will be same as in my notebook if not please change accordingly.Output of this notebook will be saved as two files i.e “data” and “new_target”.

3. The second notebook i.e “training the CNN” will have 7 cells in which the second fourth cell will rull for not much that 10 minutes since it should complete 20 Epochs.This notebook should produce several new models in different folders. Also should be able to observe a visualization for training and testing data accuracy as well as loss.

4. The third notebook i.e “detecting masks” will have 3 cells in which the second cell will be used for training the model [ model-017.model ] will be used for execution of the evaluator.Although we can use one of the produced output from the second notebook like “model-001,model” and test the output.

File Path Structure:

Deep_learning_project_A04228048
|--Face_Mask_Detection ----> Downloaded files from Drive can be stored here.
|  |--1.0 data preprocessing.ipynb
|  |--2.0 training the CNN.ipynb
|  |--3.0 detecting Masks.ipynb
|  |--requirements.txt
|
|--Readme_file.txt 

Credits and Links:
The original dataset is prepared by Prajna Bhandary and modified by JUGAL KISHORE accordingly to the usecase and available is at Github.

NOTE:
For Swift  Execution of notebook in Jupyter:
Please type Shift and Enter or could run all cells together.
