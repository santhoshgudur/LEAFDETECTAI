# LEAFDETECTAI - EVALUATING ML AND DL PARADIGMS FOR SUPERIOR LEAF DISEASE IDENTIFICATION

## ABSTRACT
This research evaluates the efficacy of seven ML models - Logistic Regression, Linear Discriminant Analysis, K-Nearest Neighbors, Decision Trees, Random Forest, Naïve Bayes, and Support Vector Machine - and two DL models, NASNetMobile and MobileNetV2, for apple leaf disease detection using the PlantVillage dataset. The focus is on diseases like Apple Scab, Black Rot, and Cedar Apple Rust. Feature extraction techniques like Hu Moments, Haralick texture, and Color histograms are utilized for ML models, while MobileNetV2 and NASNetMobile leverage transfer learning. Stratified K-Fold Cross-Validation ensures robust model evaluation. Among ML models, Random Forest emerged as the most accurate with an accuracy of 95.21%, demonstrating its potential in disease detection. However, MobileNetV2 outperformed all models, achieving an overall accuracy of 98%, underscoring its superiority in classifying plant health conditions. This research highlights MobileNetV2's advanced efficiency and reliability, making it a promising tool for automated plant disease diagnosis, and revolutionizing agricultural disease management practices with its precision and recall capabilities.

## Dataset Description
The Plant Village dataset is a comprehensive collection of 54,309 images covering 14 different plant species, including Apple, Blueberry, Cherry, Corn, Grape, Orange, Peach, Bell Pepper, Potato, Raspberry, Soybean, Squash, Strawberry, and Tomato. This dataset encompasses images depicting 17 fungal diseases, 4 bacterial diseases, 2 mold (oomycete) diseases, 2 viral diseases, and 1 disease caused by a mite. Additionally, images of healthy leaves, devoid of visible disease symptoms, are included for 12 plant species. (Sai & Patil, 2022)
Dataset Link: https://github.com/spMohanty/PlantVillage-Dataset

The data for this study was sourced from the "Color" section found in the "raw" folder of the PlantVillage dataset. The modeling in this study is specifically centered on the analysis of Apple Leaves data. The train and test datasets are structured into two folders: Diseased and Healthy. The Diseased Folder encompasses images of leaves affected by Black Rot, Cedar Apple Rust, and Apple Scab, labeled as diseased or unhealthy. On the other hand, the Healthy Folder contains images of green and healthy leaves.

## Technologies Used
### Deep Learning Models
- TensorFlow
- Keras
- NumPy
- Pandas
- Matplotlib

### Machine Learning Models
- Scikit-learn
- NumPy
- Pandas
- Matplotlib

## Skills Required
- Proficiency in TensorFlow and Keras (for deep learning models)
- Proficiency in Scikit-learn (for machine learning models)
- Understanding of neural networks and CNNs
- Understanding of traditional machine learning algorithms
- Ability to preprocess image data
- Knowledge of model evaluation and hyperparameter tuning

## Results
### Comparative Analysis of ML Models for Apple Leaf Disease Detection
![image](https://github.com/santhoshgudur/LEAFDETECTAI/assets/40780764/3272a7ee-a3f1-4623-ba56-c7155c1198dd)

### Comparative Performance of DL Models for Leaf Disease Detection
![image](https://github.com/santhoshgudur/LEAFDETECTAI/assets/40780764/cff75015-75a4-4dfd-a273-2c3ec700766d)

## Conclusion
Based on the comparative analysis, MobileNetV2 is chosen as the best model for detecting diseases in apple leaves. Its advanced capability in accurately classifying plant health conditions, coupled with its efficiency and reliability across various metrics, underscores its potential to significantly contribute to sustainable and efficient agricultural practices. The adoption of MobileNetV2 could facilitate early and accurate disease detection, thereby enhancing disease management strategies and revolutionizing precision agriculture.

The selection of MobileNetV2 as the best model is grounded in its consistent superiority in key performance indicators and its suitability for practical deployment in real-world agricultural settings, making it a valuable tool in advancing the field of agricultural technology.

