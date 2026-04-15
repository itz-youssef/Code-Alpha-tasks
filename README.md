Developed a robust deep learning-based Optical Character Recognition (OCR) system capable of identifying and classifying 47 different classes of handwritten alphanumeric characters (digits and both uppercase/lowercase letters) with high accuracy.                                                                                                                               Architected a custom Convolutional Neural Network (CNN) optimized for feature extraction from image data.

Implemented a robust data preprocessing pipeline, including custom image transformations (handling 90-degree rotations and flipping) and normalization.

Applied regularization techniques, such as Dropout layers, to mitigate overfitting and enhance the model's ability to generalize to unseen data.

Developed a visualization pipeline to display inference results, directly comparing model predictions against ground-truth labels.


----------------------------------
Overview: Engineered a complete machine learning pipeline to analyze structured medical data and predict the malignancy of breast cancer tumors based on cell characteristics. The project heavily prioritized diagnostic accuracy to minimize critical medical errors.

Key Features:

Conducted comprehensive Exploratory Data Analysis (EDA), utilizing correlation heatmaps and boxplots to identify highly impactful medical features.

Executed feature scaling using StandardScaler to ensure the optimal performance of distance-based algorithms like Support Vector Machines (SVM) and Logistic Regression.

Benchmarked four distinct classification algorithms (SVM, Random Forest, XGBoost, Logistic Regression), ultimately evaluating them based on the Recall metric to prioritize patient safety.

Utilized Confusion Matrices to evaluate the model's capacity to minimize False Negatives, a critical requirement in healthcare diagnostics. <br><strong style="color: var(--primary);"> Technologies:</strong> Python, Scikit-learn, XGBoost, Random Forest, SVM, Pandas, Seaborn.
