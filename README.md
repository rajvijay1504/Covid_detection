**Covid Detection for X-ray Diagnosis**

**Overview:**
This project focuses on developing a machine learning model for COVID-19 detection using X-ray images. Leveraging a dataset containing X-ray images of COVID-positive and COVID-negative cases, we aim to build an image classification system to aid in the diagnosis of COVID-19.

**Key Steps:**
1. **Data Preparation and Visualization:**
   - Mounted Google Drive to access the dataset.
   - Visualized sample X-ray images for both COVID-positive and COVID-negative cases.
   - Enhanced image quality through histogram equalization.

2. **Data Augmentation and Preprocessing:**
   - Utilized ImageDataGenerator for preprocessing and augmentation.
   - Preprocessed images by rescaling, rotating, shifting, flipping, shearing, and zooming.

3. **Feature Extraction:**
   - Extracted additional pixel intensity features like mean, median, standard deviation, skewness, and kurtosis.
   - Computed Histogram of Oriented Gradients (HOG) features for image representation.

4. **Model Training and Evaluation:**
   - Split the dataset into training and testing sets.
   - Trained various machine learning models including SVM, Logistic Regression, KNN, Decision Tree, Random Forest, and Naive Bayes.
   - Evaluated model performances using accuracy, confusion matrix, and classification report.

**Results:**
- SVM model achieved an accuracy of 82.67%, demonstrating promising performance among the models tested.
- Feature extraction techniques like HOG and additional pixel intensity features significantly contributed to model accuracy.

This project aims to contribute to the fight against COVID-19 by providing a reliable and efficient tool for diagnosing the disease through automated analysis of X-ray images.
