# classification-of-respiratory-sounds
To classify the respiratory sounds using deep learning.

Chronic Respiratory Diseases (CRDs), such as Asthma and Chronic Obstructive Pulmonary Disease (COPD), are leading causes of deaths worldwide. 
They can be managed by close monitoring of symptoms to prevent worsening of the condition. One key symptom that needs to be monitored is the occurrence of wheezing sounds
during breathing since its early identification could prevent serious exacerbations. Since wheezing can happen randomly without warning, a long-term monitoring
system with automatic wheeze detection could be extremely helpful to manage these respiratory diseases.

A deep CNN model that classifies respiratory sounds based on Mel-spectrograms and MFCC. By implementing a patient specific model tuning strategy that 
first screens respiratory patients and then builds patient specific classification models using limited patient data for reliable disease nature detection. 
In training, Mel-Spectrograms are transposed and wrapped around the time-axis to help allow the network to learn to identify features occurring at arbitrary
times within the recording. The result from given features and data for the trained model can be analysed. 

In this project, we propose the use of Raspberry pi operating system and jupyter notebook for making the classified model.
