# Python Speech recognition

A command speech recognition system is built to assist the driver to interact with the surrounding environment and remove the distraction that may cause car crashes. By using the dataset provided from [TensorFlow Speech Recognition Challenge](https://www.kaggle.com/c/tensorflow-speech-recognition-challenge/data) as a challenge, our models are trained to recognize them well.

Different combinations of ensemble learning between models have been carried out targeting to get the best accuracy on submission dataset ( 150k samples). The best combination of models is Densenet (randomly initialized) (semi supervised), Wideresnet, Resnext (semi supervised) ,DPN92 and RNN (32*32) (semi supervised). This combination has achieved accuracy of 0.9755, 0.973 and 90.238 on the validation, test and submission set respectively. This achievement placed our team on the 25th out of 1314 competitors on the competition.

This project deals with keras, pytorch, multi-classifications problem, speech analysis, semi-supervised learning, augmentation of speech, and GANs.

All the project details could be found in this paper [Dual_Mode_Crash_Avoidance_Paper (https://github.com/user/repo/blob/branch/other_file.md)


The code is in the attatched notebooks 
