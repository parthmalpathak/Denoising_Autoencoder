# Deblurred and Denoised Reconstruction

A Deep Learning based pipeline for deblurred and denoised 3D Reconstruction

## Overview
### Motivation
Unmanned Aerial Vehicles (UAVs) have gained a lot of a attraction recently due to their applications in surveillance, structural inspection and tracking. While researching with DIY UAVs, a general observation was made that video output coming from UAVs camera had motion blur due to the constant hovering of the UAV. 
### Denoising Autoencoders
Autoencoders present an efficient way to learn the data representation. It also helps with dimensionality reduction and feature extraction.The purpose of denoising autoencoders is to remove noise. It acts like a customised denoising algorithm tuned to the custom data. 
If trained on a specific type of data, denoising autoencoders are capable of removing noise or motion blur from similar type of data which may be unseen to the model. In simple words, Denoising autoencoders are fed noisy images as inputs. The reconstructions from these Denoising Autoencoders is compared with sharp images during loss calculations to minimize the loss function. This helps the Denoising Autoencoder model to learn to remove noise from unseen images.
