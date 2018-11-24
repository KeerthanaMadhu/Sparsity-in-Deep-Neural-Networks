This folder consists of the code to implement Deep Belief Network and Deep Adaptive Network.
To run this file this system needs to have python, tensorflow and scikit-learn installed.As the training process 
takes considerable amount of time, these files were run on google cloud instance.

1. The file DAN_DBN.ipnyb consists of code to build and train the networds DBN and DAN.
   After these networks are trained, the outputs of the training data and testing data from the DAN and DBN 
   networks are stored. 
   The code from the link 'https://github.com/JosephGatto/Simplified-Restricted-Boltzmann-Machines.git'
   was used for DBN network and a few fucntionalities were added on top of it for implementing DAN model.
2. These stored values are used as inputs in the second file 'classification/ipnyb'. On running this file,
   classification accuracy is obtained.