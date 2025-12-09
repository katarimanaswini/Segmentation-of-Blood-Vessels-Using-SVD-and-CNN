# Segmentation-of-Blood-Vessels-Using-SVD-and-CNN
This project presents a hybrid medical image segmentation that combines Singular Value Decomposition (SVD) based preprocessing with a U-Net CNN for accurate retinal blood vessel segmentation.
The goal is to enhance vessel visibility in retinal fundus images and improve early detection of diseases such as diabetic retinopathy, glaucoma, and age-related macular degeneration.

⭐ Project Overview

This repository contains:
	•	A custom SVD preprocessing module applied on the green channel of retinal images
	•	A U-Net deep learning model built in TensorFlow/Keras for vessel segmentation
	•	A full pipeline including:
	  Preprocessing
	  Patch extraction
	  Training
	  Evaluation
	  Reconstruction
	  Single-image inference

The hybrid approach improves feature clarity, reduces noise, and helps the CNN detect thin, low-contrast blood vessels more effectively.

🔬 Why Use SVD + CNN?

The combination of SVD and CNN provides two powerful advantages:

SVD Benefits
	•	Extracts dominant structural information |
	  Removes noise by retaining major singular values |
	  Highlights vessel edges and intensity variations |
	  Enhances green-channel contrast—the most informative retinal channel

CNN Benefits
	•	Learns hierarchical vessel patterns automatically |
		Segments thin and complex vascular structures |
		Works well on medical images with limited data |
		U-Net architecture preserves spatial details via skip connections

    


Together, SVD simplifies and enhances the image structure while CNN learns to segment vessels accurately.
