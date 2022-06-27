# Robotic Manipulation of Transparent Objects
## Transparent Object Dataset (TOD)
The dataset used for this project can be found at https://sites.google.com/view/keypose 
## KeyPose
The code for KeyPose was used for all of the experiments. It can be found at https://github.com/google-research/google-research/tree/master/keypose
The main modifications were to gen_tfrecords.py, predict.py and trainer.py. For the architecture changes the code for estimator.py, inputs.py, nets.py and trainer.py were changed. 
## TransLab
The TransLab model was finetuned on the all of the objects from TOD other than the ball object due to a lack of masks. The finetuned model is available at https://drive.google.com/file/d/1--2kE27sN-WU4aidWB6EPOKBVO0Ap67Q/view?usp=sharing. 

## Results
The visualisation for every model can be found at https://drive.google.com/drive/folders/18Xp3qCgg3Ab8kIZR62r-Pbnf0NHWx_bQ?usp=sharing
