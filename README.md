# The COVID-19 Face Mask Image Classification
The project aims to explore the applicable machine learning model for classifying whether individuals wear the mask appropriately, incorrectly, or did not wear it at all. To process, we download 4559 raw images from Kaggle. We processed the image data set into two representation ways, the raw pixel representation and color representation.  70\% of each data set is used for training, while the remaining 30\% is used for testing. 20\% of the training set in each data set is accounted for validation. We selected K-Nearest Neighbors, Decision Tree, Bagging (with Decision Tree), Random Forest, XGBoost, and Logistic Regression algorithms to train and test. The tuning strategy is used in each algorithm to improve the test accuracy. In addition, We evaluate the model prediction outcome by the F1 Score and McNemar's Test. Consequently, we find that the XGBoost, with a test accuracy of 94.88\%, is the best machine learning model for this project.

Since the size of processed data in "raw_images.csv" is larger than the upload limit for Github, we are unable to upload our processed data to Github. For anyone who is interested in it, please refer to image_processing.ipynb to download it.

Here is the visualized summary about the performances for each models we trained. We have evaluated both accuracy score and F1 score.

![Accuracy vs  F1 Score](https://user-images.githubusercontent.com/44512502/144944432-035e0a8d-73f8-43e5-b547-03307946b595.png)

For full details about our project, please reference to our report. [Final report.pdf](https://github.com/Szhang577/STAT_451_Final_Project/files/7664448/Final.report.pdf)
