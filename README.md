
# A Large Scale Fish Classification using Machine Learning




## Overview
This dataset contains 9 different seafood types collected from a supermarket in Izmir, Turkey for a university-industry collaboration project at Izmir University of Economics, and this work was published in ASYU 2020.For each class, there are 1000 augmented images and their pair-wise augmented ground truths.Images were collected via 2 different cameras, Kodak Easyshare Z650 and Samsung ST60.Therefore, the resolution of the images are 2832 x 2128, 1024 x 768, respectively.Before the segmentation, feature extraction, and classification process, the dataset was resized to 590 x 445 by preserving the aspect ratio. After resizing the images, all labels in the dataset were augmented (by flipping and rotating).
At the end of the augmentation process, the number of total images for each class became 2000; 1000 for the RGB fish images
and 1000 for their pair-wise ground truth labels.

## Key Features
1.Modeling: Three machine learning algorithms, namely Decision Tree, and Random Forest, are individually trained and evaluated to detect fraudulent transactions.
 2.Ensemble Learning: An ensemble model is constructed using the VotingClassifier technique, which combines predictions from multiple base models (Logistic Regression, Decision Tree, Random Forest) to improve overall performance and robustness. 
 3.Evaluation: Model performance is assessed using metrics such as accuracy, precision, recall, and F1-score. Confusion matrices and classification reports are generated to provide detailed insights into model performance.

## Technologies Used
Python: Programming language used for model training and evaluation. scikit-learn: Python library for machine learning tasks including model training and evaluation. Pandas: Python library for data manipulation and analysis Seaborn: Python library for visualization.
