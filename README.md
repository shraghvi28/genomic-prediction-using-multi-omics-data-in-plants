# genomic-prediction-using-multi-omics-data-in-plants
a deep neural network based method for genomic prediction using multi omics data in plants



Problem:
Genomic selection is crucial for plant breeding, helping predict desirable traits from genetic data. Traditional methods like GBLUP (Genomic Best Linear Unbiased Prediction) struggle with complex genotype-phenotype relationships due to their linear assumptions. While machine learning (ML) methods like SVR (Support Vector Regression) improve accuracy, they still face challenges in handling high-dimensional genomic data efficiently.

Limitations of Existing Methods:
- Linear models (e.g., GBLUP) fail to capture non-linear genetic interactions.
- Machine learning models (e.g., SVR, LightGBM) require extensive hyperparameter tuning and may struggle with high-dimensional datasets.
- Deep Learning models need large datasets and optimization to prevent overfitting.

Proposed Method:
We implement DNNGP (Deep Neural Network Genomic Prediction), a deep learning-based model, to enhance genomic selection accuracy by:
1. Using deep neural networks to model complex non-linear genetic interactions.
2. Employing PCA-transformed genomic features (PC1–PC251) from the Wheat599 dataset.
3. Comparing DNNGP’s performance against SVR to evaluate prediction improvements.
