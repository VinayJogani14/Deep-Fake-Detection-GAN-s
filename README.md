# Deep-Fake-Detection-GAN's

DeepFake Detection using GANs and Perceptual Image Analysis
This project utilizes Generative Adversarial Networks (GANs) to classify DeepFake content by leveraging perceptual differences in images. The core approach integrates a novel framework called MRI-GAN, which generates MRI-like outputs for input images. These MRI outputs highlight synthesized artifacts in DeepFake images, whereas genuine images produce black MRI outputs, making the classification process more effective.

Key Results:

A plain frames-based model achieves 91% test accuracy using the DeepFake Detection Challenge Dataset.
The MRI-GAN model, which incorporates the Structural Similarity Index Measurement (SSIM) for detecting perceptual differences, achieves 74% accuracy.
Further improvements can be made by refining loss functions, adjusting hyperparameters, and using advanced perceptual metrics.

The project is a comprehensive effort involving data preprocessing, model training, and result evaluation. You can replicate this work following the provided setup instructions and using the datasets linked within the repository.

Link: https://github.com/pratikpv/mri_gan_deepfake

