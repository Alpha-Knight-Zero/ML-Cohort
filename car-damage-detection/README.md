This is a readme file for the Car Damage Detection task of the ML Cohort.

It was done on Google Collaboratory Noebooks using Google Drive Storage , Tensorflow Object Detection API , Tenserflow v2.8 and Python 3.9 along with other requisites that are mentioned in the collab notebooks that contain the driver code for training and evaluation for this task.

To reproduce the the task as done by me :

Step 1: Copy the Tenserflow folder using this link to root directory in your Google Drive.
(https://drive.google.com/drive/folders/1U3uYkCcehNstc9XgBQ15mdo1sloDT_LC?usp=sharing)

Step 2: Copy the 2 ".ipynb" files in the Collab Notebooks folder and paste them in your root directory on Google Drive.

Step 3: Run the Train_Object_Detection_model_TF2.ipynb file to train the model.

Step 4: Inference graph and testing on images can be done by following instructions in the aforementioned file (notebook).

Step 5: Run the Eval_Object_Detection_model_TF2.ipynb file for evaluating the model on the test set.

The default Train_Object_Detection_model_TF2.ipynb file will train the model using "SSD MobileNet v2" model on the images given in "Tenserflow/workspace/training_demo/images/train" folder.

The default Eval_Object_Detection_model_TF2.ipynb file will evaluate the model on the images given in "Tenserflow/workspace/training_demo/images/test" folder.

The Graphs obtained while training models "SSD MobileNet v2" and "ResNet 50" are shown in the screenshots present in the Plots folder. (They are aptly named so as to not create confusion.)

Some of the results obtained were as follows :

Drive Links:

Tenserflow Folder : https://drive.google.com/drive/folders/1U3uYkCcehNstc9XgBQ15mdo1sloDT_LC?usp=sharing

To the Datset used for training : https://drive.google.com/drive/folders/1mDZtRYOAGXngZLRo7nXadUN5LLTaxnut?usp=sharing

To the training notebook : https://colab.research.google.com/drive/1Eo8R_J6iCzr5rVrrljbixlafFftFNL47?usp=sharing

To the evaluation notebook : https://colab.research.google.com/drive/11-6_V4rnFglD6yAPVlaVzP3hsUa7C_lr?usp=sharing
