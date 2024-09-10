# Astrophysics-Analysis-Projects

## Overview
This project focuses on using machine learning techniques, specifically Artificial Neural Networks (ANNs) and Convolutional Neural Networks (CNNs), to classify astronomical images from the CORNISH survey. The goal was to differentiate between ultra-compact HII regions, planetary nebulae (PNE), and background galaxies (RGs) based on their radio and infrared emission patterns. The CORNISH survey data were combined with mid-infrared observations from the Spitzer Space Telescope (GLIMPSE survey).

## Techniques Used
- **Data Processing**:
  - Used **Astropy** to read and manipulate FITS image data.
  - Preprocessed 2D image arrays with **NumPy** and **ndimage** to prepare the data for input into ANN and CNN models.
  
- **Machine Learning**:
  - Implemented an **Artificial Neural Network (ANN)** to classify images based on their 8.0 μm infrared emissions.
  - Developed a **Convolutional Neural Network (CNN)**, incorporating additional infrared bands (4.5 and 5.8 μm) to improve classification accuracy.
  - Hyperparameter tuning to optimize model performance (learning rate, epochs, batch size, etc.).
  
- **Evaluation**:
  - Assessed the model’s performance using metrics such as accuracy, precision, and recall.
  - Utilized **Scikit-learn** for performance evaluation and comparisons between the ANN and CNN classifiers.

## Key Outcomes
- Successfully classified HII regions, PNE, and RGs with both ANN and CNN architectures.
- Demonstrated a significant performance improvement in the CNN model due to the inclusion of additional infrared bands.
- Optimized model accuracy through hyperparameter tuning, resulting in enhanced differentiation between the three object types.
