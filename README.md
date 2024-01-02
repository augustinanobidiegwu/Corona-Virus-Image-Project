# Corona-Virus-Image-Project
This project focused on analyzing and classifying COVID-related X-ray images categorized into chest, knee, and wrist classes. The data preprocessing steps included converting images to grayscale, normalizing pixels, performing feature extraction, and augmenting images.

It involves using chest, wrist, and knee X-ray images sourced from different datasets on Kaggle. The chest images (1600) are from the CoronaHack Chest X-ray dataset, the wrist images (2000) are from the RSNA Bone Age dataset, and the knee images (1000) are from the MedicalExpert-I folder in the Digital Knee X-ray dataset.

The task includes using a bar chart to visualize the data distribution, merging these pictures into a single NumPy array for validation and preprocessing, and then carrying out multiple methods:

Model Training and Validation (Neural Network): Using a neural network-based machine learning architecture, the test set is first classified using an unmodified dataset.

Image Augmentation: Classifying the test set using a neural network-based machine learning architecture after balancing the training data classes through methods such as image augmentation.

Feature extraction: extracting features (e.g., Harris, SIFT, SURF, HOG) from the dataset and applying several Machine Learning architectures (e.g., NN, CNN, SVM, Random Forests, Naïve Bayes) for classification.

Data undersampling: employing various ML architectures for test set classification while maintaining dataset balance through undersampling methods.

A DataFrame with the model names, F1-Score, Precision, Recall, and an explanation of the assessment methodology will be used to assess the findings.

The NN architectures performed well, with the second design performing better on all criteria. The RandomForest-trained models performed quite well as well, highlighting the reliability of these methods in categorizing X-ray pictures related to COVID-19. This was particularly true when employing the HOG feature and undersampling strategies.
