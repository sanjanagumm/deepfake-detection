DeepFake, which is a portmanteau of the terms ‘deep learning’ and ‘fake’, is a new vein of AI generated fake videos synthesized using generative ML models. They can achieve high degrees of realism and have thus been used in malignant ways, manipulating people into believing something is real when it is not. 

The proposed model for DeepFake Face Identification uses a CNN-based approach to detect manipulated media, given that CNNs are particularly well suited for image and video analysis tasks.

The incorporation of Explainable AI (XAI) allows for the detection process to be more interpretable by the user, by highlighting the features that led to the model’s classification as real/fake.

Dataset used: OpenForensics dataset, which contains over 190k images (both real and fake) split into train, test, and validation sets.

This repository contains:
1. cnn-deepfake.ipynb, where the CNN Model was built, which classifies an image as real or deepfaked.
2. deepfake-detector-model.keras, the model.
3. xai-deepfake, the Explainable AI using LIME.
