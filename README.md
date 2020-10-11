# Handwritten Character Recognition using Neural Networks
## Problem Statement:
To detect and recognize english handwritten characters ie.Alphabets from A-Z using Neural Networks.
## Requirements  

### Environment:
Anaconda Environment and Jupyter Notebook.

### Downloading Dataset:
Download the zip folder from the link: https://www.kaggle.com/sachinpatel21/az-handwritten-alphabets-in-csv-format/download  and extract the following file: 
>A_Z Handwritten Data.csv  

Add the extracted csv file to the folder:
>dataset cv/  

### Converting CSV file to Dataset Images:
Run the following notebookfile:  
    
    extracting images.ipynb

The dataset images will be added to the folder:  
>alphabets dataset/  
### Libraries:
Download and install the following libraries in Anaconda environment using the anaconda prompt:  
#### Tensorflow
    conda install tensorflow
#### tqdm
    conda install -c conda-forge tqdm
#### OpenCV
    conda install -c conda-forge opencv
#### Pillow
    conda install -c anaconda pillow
#### Numpy
    conda install -c anaconda numpy  

## Training and Testing the neural network model 
Label the image containing a handwritten character to be tested by the network as "test.jpg" and add it to the folder:  
>test/  

Run the following notebook to train and test the neural network:  
    
    handwriting character detection.ipynb
The neural network model hence detects and recognizes the handwritten alphabet present in the test image.

