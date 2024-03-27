This project is about brain tumor detection using machine learning techniques.


1. Mounting Google Drive :
   - The code mounts Google Drive to access the dataset stored there.

2. Loading and Preprocessing Data:
   - It loads images of brain tumors and their corresponding labels from the unzipped dataset.
   - The images are resized to a uniform size (200x200 pixels) to ensure consistency.
   - The images are converted into a 1D array by reshaping them, making them suitable for machine learning algorithms.

3. Data Splitting:
   - The dataset is split into training and testing sets using the `train_test_split` function.
   - This allows the model to learn from the training data and evaluate its performance on unseen data (testing data).
   - ![image](https://github.com/gayatripardeshi17/4th_SEM_PROJECT/assets/149011159/37f84409-68e8-4f4e-8d6d-a5a0da516abc)


4. Feature Scaling:
   - The pixel values of the images are scaled to the range [0, 1] by dividing them by 255.
   - This step helps improve the model's performance.

5. Feature Selection using PCA:
   - Principal Component Analysis (PCA) is applied to reduce the dimensionality of the data while retaining most of its variance.
   - PCA selects the most informative features (principal components) that capture the essential characteristics of the images.

6. Model Training:
   - Two machine learning models are trained: Logistic Regression and Support Vector Machine (SVM).
   - The models are trained on the training data to learn the relationship between the image features and the tumor labels.

7. Model Evaluation:
   - The trained models are evaluated on the testing data to assess their performance.
   - The accuracy score is calculated to measure the proportion of correctly classified images.

8. Prediction:
   - The SVM model is used to make predictions on the testing data.
   - The predicted labels are compared to the actual labels to identify misclassified samples.
   - ![image](https://github.com/gayatripardeshi17/4th_SEM_PROJECT/assets/149011159/b9eb8476-fa65-4bbe-907b-33f03637782f)


9. Visualization of Results:
   - A few misclassified samples are visualized to gain insights into the model's errors.
   - The model's predictions on a subset of images from the testing set are displayed along with the corresponding actual labels.
     ![image](https://github.com/gayatripardeshi17/4th_SEM_PROJECT/assets/149011159/fd873efc-48ec-4bc5-9678-0e0b1bd4c7bd)
![image](https://github.com/gayatripardeshi17/4th_SEM_PROJECT/assets/149011159/0c051401-c135-49f9-b5bd-393526fdad75)


In summary, this project demonstrates the use of machine learning techniques for brain tumor detection.
It involves data preprocessing, feature selection, model training, evaluation, and visualization of results.
The goal is to develop a model that can accurately classify brain tumors based on their image characteristics.
