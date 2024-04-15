# WhaleTailCNNProject
Final Project for AA501

This code implements a Convolutional Neural Network (CNN) to classify individual humpback whales based on the unique patterns on their tails (flukes).

Key Points:

Data: The code uses images of humpback whale tails from a directory named resized.

Image Preprocessing: Images are resized to 150x150 pixels and augmented (rotated, shifted, zoomed etc.) to improve model robustness.

Model Architecture: A CNN with convolutional and pooling layers is used to extract features from the images. Dense layers are used for classification.

Training: The model is trained on a portion of the data (80%) to distinguish between known and new whale tails (binary classification). The remaining data (20%) is used for validation.

Testing: The trained model can be used to predict if a new image belongs to a known whale or a new individual.

Output: The code saves the trained model (whale_classification_model.h5) and interprets the prediction for a single test image.

Note: the data set seems to be too large to upload to GitHub so providing a link to the data source here: https://www.kaggle.com/datasets/sairam6087/humpbackwhalefinal

I have uploaded a smaller data set used to initially test the code on ~100 images. The full data set is closer to ~200k images

IN addition, the models built are two big to drop into this GitHub repository, each coming in at around 40 MB
