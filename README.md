# Leaf Disease Classification using Image Processing and Machine Learning

This repository contains code for a project that classifies leaf diseases. The project uses image processing techniques and machine learning algorithms to classify leaves into four categories: Black Rot, Measles, Healthy, and Leaf Blight.

## Project Overview

1. **Background Removal**: The first step in the process is to remove the background from the images. This is done using thresholding techniques.

2. **Green Part Removal**: After the background has been removed, the green parts of the diseased leaf are removed using KMeans clustering.

3. **Feature Extraction**: The next step is to extract features from the images. This is done using the Grey Level Co-occurrence Matrix (GLCM).

4. **Feature Selection**: Principal Component Analysis (PCA) and Relief are used for feature selection.

5. **Classification**: Finally, the Support Vector Machine (SVM) algorithm is used for classification.
