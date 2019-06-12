# Classify-images-as-either-melanoma-or-benign-nevus

There has been a steady increase in the incidence of skin cancer worldwide, with
a high rate of mortality. Early detection and segmentation of skin lesions are crucial for
timely diagnosis and treatment, necessary to improve the survival rate of patients. The
objective of this challenge is to classify images of skin lesions as either benign or
melanoma. In order to do that, we will do a chain of work: (a) image segmentation to
separate the lesion area from the background skin, (b) extraction of image features for
classification purposes, and (c) final classification using statistical methods.

For the data, we have a data-set of 1000 RGB images of skin lesions with their
relative segmentation. The training dataset contains 700 of those images and we only
have the classification of the training dataset. While, we need to estimate or predict the
correct class (benign or malign) for the rest 300 images in the test dataset.

I used Python 3 as programming language and imported panda, numpy, cv2,
scikit-learn and etc.

I complete this project by several steps like feature extraction, pre-processing, several classification algorithms(LDA, QDA, KNN, SVM, Random Forest and Bagging based on Decision Tree etc) and some predictions. 
