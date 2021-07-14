# Brain MRI Segmentation using U-Net

This Keras model uses U-Net to segment tumors in brains with 99.5% validation accuracy
# Packages used

python v3.8  
tensorflow v2.5  
keras v2.2. 5  
OpenCv v4.5.2  
numpy v1.21.0  
pandas v1.2.4  
matplotlib v3.4.2  
seaborn v0.11.1  
glob 7.1.7  
tqdm v4.61.1  
scikit-learn v0.24.2  
scikit-image v0.18.0  
Out of these you only need tensorflow and keras for predictions.  

# Dataset
The datatset being used to train the model is taken from kaggle.  
You can download it from [here](https://www.kaggle.com/mateuszbuda/lgg-mri-segmentationt)  
The dataset consists of 3929 total images of brain MRI scans.  


# Instructions

If you want to train the model, run all the cells in Brain_MRI_Segmentation.ipynb  
To use the model on predictions on your own images, load the dataset from predict cell and then run the prediction code on your own image  
(further instructions are presented as markdowns in notebooks)  
