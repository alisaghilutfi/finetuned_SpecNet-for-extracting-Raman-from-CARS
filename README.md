# finetuned_SpecNet
 finetuned_SpecNet for extracting Raman from CARS
 In this work, the Raman signal is extracted from the CARS spectrum by using a convolutional neural network. The model architecture is adapted from the original SpecNet model. The model is pre-trained with synthetic data and fine-tuned with semi-synthetic data based on two sets of semi-synthetic spectra. The experimental results show that the model achieves 86% accuracy in predicting the Raman signal of semi-synthetic data. In addition, the sensitivity of the model performance to varying levels of noise is analysed. Based on standard metrics, the model performance decreases with the increasing level of noise in a non-linear manner. Finally, the prediction capability of the fine-tuned SpecNet model was evaluated on the four experimental CARS spectra and the results were found to be better compared to SpecNet.

Paper title: "Semi-synthetic data generation to fine-tune a convolutional neural network for retrieving Raman signals from CARS spectra"

By Ali Saghi, Rajendhar junjuri, Lasse Lensu, and Erik M. Vartiainen
