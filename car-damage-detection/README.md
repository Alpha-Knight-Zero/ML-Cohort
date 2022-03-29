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

![image](https://user-images.githubusercontent.com/65271592/160597845-9fc04a04-d735-41a0-841f-64951df5ca5f.png) ![image (1)](https://user-images.githubusercontent.com/65271592/160597903-ae709d8d-a24a-4b1c-8a26-61e51df3c098.png)

![image (2)](https://user-images.githubusercontent.com/65271592/160597909-ba839918-1493-486d-9bb8-3fb9566b3e57.png) ![image (3)](https://user-images.githubusercontent.com/65271592/160597925-e3cbaa06-a29b-4742-800c-763833472f72.png)

![image (4)](https://user-images.githubusercontent.com/65271592/160597941-3e4440ab-7e4a-473a-bfe3-8d6408e7db3e.png) ![image (6)](https://user-images.githubusercontent.com/65271592/160597974-1d1ead42-22eb-4e3a-af95-f669b40a8e4e.png)


Drive Links:

Tenserflow Folder : https://drive.google.com/drive/folders/1U3uYkCcehNstc9XgBQ15mdo1sloDT_LC?usp=sharing

To the Datset used for training : https://drive.google.com/drive/folders/1mDZtRYOAGXngZLRo7nXadUN5LLTaxnut?usp=sharing

To the training notebook : https://colab.research.google.com/drive/1Eo8R_J6iCzr5rVrrljbixlafFftFNL47?usp=sharing

To the evaluation notebook : https://colab.research.google.com/drive/11-6_V4rnFglD6yAPVlaVzP3hsUa7C_lr?usp=sharing
