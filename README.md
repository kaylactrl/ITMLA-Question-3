The Systems Design steps: 
1.	Firstly, the dataset needs to be loaded, it is important that the dataset includes both classes of images that the model needs to learn from. 
2.	Once the images are uploaded, using the function image enhancement it requires histogram equalization and adaptive thresholding to each image, this improves the contrast and details of the images which makes it easier for the feature extraction process. 
3.	Feature extraction, edge detection is used to each image using the canny algorithm. The edge detection helps in detecting boundaries and shapes in concrete blocks influencing the classifiers capability to distinguish between defective and defectless blocks. 
4.	Normalization, using StandardScaler the features are normalized to perform and ensure features don’t over dominate each, due to the scale. 
5.	The dataset is then split into training and testing dataset, which is crucial for evaluating the model’s performance. It also ensures that the model can universalise other data than the examples it was trained on. 
6.	Classifier training, this is trained on the processed dataset. 
7.	Classifier testing, the classification report provide insights on how the model can differentiate between defective and defectless concrete blocks. 


•	Adaptive Thresholding: it was chosen because of the efficiency in picture improvement, it boots image contrast and the flexibility to change lighting, which is critical, because the robot will be navigating inside and outside the warehouse. 
•	Edge Detection: its ability to highlight edges with high intensity this is critical for detecting any flaws in the concrete blocks. 

The Classification of unseen images 
•	The classification report will provide measures like accuracy, precision, recall and the F1 score for evaluating the trained model’s performance. The intensity level of accuracy and recall scores for both class demonstrate the models ability to properly identify faulty and defectless blocks. 
•	The feature extraction and normalization methods is used to categorize unseen pictures before the trained model can predict the classed. The models metrics provide credence in predicting with data. 

