# PSSPT

PSSPT (Protein Secondary Structure Prediction Tool) is a multilayer perceptron model that predicts proteins secondary structure.

This version is not good enough to predict secondary structure with high accuracy. We will develop PSSPT-2 by another deep learning model since we handle some technical (hardware) issues.

## For developers;

You should direct to the "for developers" folder to obtain benchmark dataset, MLP model source code and psspt application source code. PSSPT is a MIT licensed tool, so you can feel free to share or change source code. You can develop model or application as you wish.

We used protein secondary structure dataset from Kaggle. Here you can access the full version of the dataset:

https://www.kaggle.com/datasets/kirkdco/protein-secondary-structure-2022

## For users;

You should download the file named "psspt_setup.exe". This file will allow the PSSPT application to be installed on your computer. You can find the setup file from link of Sourceforge:

https://sourceforge.net/projects/psspt/

## Guide for installation;

When you double-click the "psspt_setup.exe" file, a window like the image below will open.

![Resim1](https://github.com/TEAM-ENICMA/PSSPT/assets/56658730/a0ee84f8-7e60-4877-8c4f-50bacd137725)

When you click on the "Install" button and continue, the installation process will start as shown in the image below.

![Resim2](https://github.com/TEAM-ENICMA/PSSPT/assets/56658730/a756a000-f4d4-494d-9298-ff2bac7147e8)

When the installation process is completed, your window will look like the image below. If you wish, you can start the program by selecting the "Launch PSSPT" option and pressing the finish button.

![Resim3](https://github.com/TEAM-ENICMA/PSSPT/assets/56658730/fb474a25-8c95-4ac3-b0b9-2c97d1a29cc1)

If you would like to run the program later, you should find the directory where the "psspt.exe" file is installed. The default directory is as shown in the image below.

![Resim4](https://github.com/TEAM-ENICMA/PSSPT/assets/56658730/0208ca1c-8090-445f-8e8f-658b18456dad)

## Guide for usage;

When you double-click "psspt.exe" file, the program runs. When the program starts running, a login screen appears as in the image below and expects you to enter a protein sequence.

![Resim5](https://github.com/TEAM-ENICMA/PSSPT/assets/56658730/4a229772-a3ee-4a14-bd32-4b8d63924bb8)

When you enter the protein sequence, PSSPT will predict the corresponding secondary structure. Your results will look like the image below. The program asks "Would you like to save results?". If you press "y" on the keyboard, PSSPT will save it as a text file. If you do not want to save, you should enter "n".

![Resim6](https://github.com/TEAM-ENICMA/PSSPT/assets/56658730/d692ad02-36fd-4507-9a55-63df3cc96fc2)

In the last step, PSSPT asks if you would like to make a new protein query as in the image below. If you would like to make a new prediction, you should enter "r". If you would like to finish the program, you should enter "q".

![Resim7](https://github.com/TEAM-ENICMA/PSSPT/assets/56658730/dcc61d30-c2b7-463f-9b14-8e5caca7ae76)
