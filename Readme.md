This particular project aims at classifying the faulty railway line 
tracks into 4 categories listed as below:
* cracks
* Flakings
* Grooves
* Joints
* Shellings
* Sapllings
* Squats
The classification is done using a Convolutional Neural Network
 (CNN) model. The model is trained on a dataset of images of railway
  line tracks. The dataset is divided into training and testing sets.
The CNN model is trained on the training set and then tested on the 
testing set.

To run the model training file on windows

1) Create a virtual environment of your choice using the 
command "python -m venv env"

2) Activate the environment :"env\Scripts\activate"  

3) clone the project here git clone "link"

4) pip install requirement.txt

5) In the file Image_Preprocessing.ipynb i have done the image 
preprocessing and the preprocessed images are stored in the folder
 "Railway_pred" . this particular images are used for training 
 and testing the dataset for better accuracies

6) After completing the training process it will create 
the model file named "rail_fault_classification.h5"

7) use this model to classify the railway line faults.
