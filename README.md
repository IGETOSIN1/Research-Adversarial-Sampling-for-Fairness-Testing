# Research-Adversarial-Sampling-for-Fairness-Testing   
This source code was written for and during research on adversarial sampling for fairness testing   <br><br>
Hypothesis-model-build.ipynb file is the source code written to build the neural network model used for the classifier. After building the model, we serialized it by using keras from tensorflow   <br><br>
Hypothesis-model-consume.ipynb file is the source code where the previously developed model was deserialized so that it can be used for prediction. It also contains several methods to manipulate the images in the dataset   <br><br>
Hypothesis-Model-Images-Noise.ipynb file is the source code where some of the images in the validation dataset was manipulated by addition of noise, and also considerable removal of noise(denoise) in addition to mechanism for layer of filteration. Some lines of code was written to loop through each of the categories of the images in the downloaded cifar-10 dataset for manipulation   <br><br>
Hypothesis-Noising-AND-Denoising.ipynb file source code is aimed for individual prediction of attacked validation dataset from the model. This particular file is more of control experiment.   
