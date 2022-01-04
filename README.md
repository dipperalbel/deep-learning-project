# Final project for the course of Deep Learning

## Components
Claudio Facchinetti ( claudio.facchinetti@studenti.unitn.it )
Alberto Bellumat ( alberto.bellumat@studenti.unitn.it )

## What is inside
- classification_test.csv: contains the predictions for the first task
- reid_test.txt contains the predictions for the second task
- Final Project - task 1.ipynb: the notebook with the code for the first task
- Final Project - task 2.ipynb: the noteboox with the code for the second task
- entire_model.pt: the model for the first task ( the training might take a lot of time )
- task2model: the model for the second task ( same reason as before )
- data.pt: the pretrained AutoEncoder for anomaly detection. Warning: it takes more than 10 hours to train the model

## How to run the code
The notebooks try to download the dataset from GDrive, but the code is specific to Google Colab; if this does not work for any reason please download the dataset and place the unzipped content in /content/dataset in the Colaboratory instance and comment the first cell of code where we try to download and unzip it.
To load the models please put them as they are on the Colaboratory instance in the /content directory.

The code should run out of the box: for efficiency purposes we did run our projects on the GPU and the models have been save from there;
be sure to be running the code on an instance with a CUDA GPU or the models won't load.

## Warnings
We are aware that the model for the first task takes a lot of memory and it could happen that it crashes due to memory issues. If so please restart the instance
and avoid training the model but use the pretrained one.
The above consideration also applies for the second task.

For the second task the evaluation takes a lot of time: on our Colab instance it took about 1 hour and a half to complete.

## Code comments
In the code there are few comments that are there to help solving issues like the ones explained before.
In the code are also present comments to provide indications about what we are doing and on how to change the loading paths, if willing to test something different.
