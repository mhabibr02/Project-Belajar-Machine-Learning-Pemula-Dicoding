# Project Belajar Machine Learning Pemula Dicoding
## Clustering Classification

<p align="center">
<img src="/Certificate/Sertifikat Belajar Machine Learning Pemula.jpg" width="80%" height="30%">
</p>

### Description
This course [Belajar Machine Learning Pemula](https://www.dicoding.com/academies/184/) from [Dicoding](https://www.dicoding.com/) provides an introduction to the world of Machine Learning, 
from basic concepts, types of ML, to how to implement them using Python. Participants will learn how ML models work, as well as how to process and analyze data to make predictions.

### Syllabus
1. Machine Learning Introduction <br>
This section provides a fundamental understanding of Machine Learning (ML), including its definition, importance, and real-world applications. You will learn how ML differs from traditional
programming and explore its role in artificial intelligence (AI).
2. Machine Learning Workflow <br>
Learn the step-by-step process of developing an ML model, from data collection and preprocessing to model training, evaluation, and deployment. This workflow ensures the systematic
development of efficient and reliable ML models.
3. Supervised Learning Classification <br>
Classification is a type of supervised learning where models learn from labeled data to categorize new data into predefined classes. You will explore popular algorithms such as
Decision Trees, Support Vector Machines (SVM), and Neural Networks.
4. Supervised Learning Regression <br>
Regression is another type of supervised learning used to predict continuous values, such as house prices or stock trends. This section covers common regression techniques, including
Linear Regression, Polynomial Regression, and Decision Tree Regression.
5. Unsupervised Learning Clustering <br>
Clustering is a key unsupervised learning technique that groups similar data points without labeled training data. You will learn about clustering methods like K-Means, Hierarchical
Clustering, and DBSCAN to find patterns in unstructured data.
6. Tehnique Feature Engineering <br>
Feature engineering is the process of transforming raw data into meaningful inputs for ML models. This section covers techniques like scaling, encoding categorical variables, handling
missing values, and feature selection to improve model performance.
7. Overfitting and Underfitting <br>
Understand the concepts of overfitting (when a model learns too much from training data and performs poorly on new data) and underfitting (when a model fails to learn patterns effectively).
Learn strategies like regularization and cross-validation to balance model complexity.
8. Optimizaiton Modelling with Hyperparameter Tunning <br>
Hyperparameter tuning is the process of optimizing a model by adjusting its parameters to improve performance. This section introduces techniques like Grid Search, Random Search, and
Bayesian Optimization to fine-tune ML models for better accuracy and efficiency.

### Result
#### Cluster 0 
- Mean temperature (°C): 30.49 (Min: 20.28, Max: 40).
- Mean humidity (%): 58.71 (Min: 41.97, Max: 80).
- Mean moisture (%): 42.67 (Min: 20, Max: 70).
- Mean nitrogen (N): 37.87 (Min: 23, Max: 46).
- Mean potassium (K): 0.92 (Min: 0, Max: 4).
- Mean phosphorous (P): 1.22 (Min: 0, Max: 18).
- Mode soil_type: Clayey.
- Mode crop_type: Maize.
- Mode fertilizer_name: 20-20.
- Analysis: This cluster shows clay soil conditions with moderate soil moisture. Nitrogen content is quite high, while potassium and phosphorus are very low. This condition is suitable
for corn plants with balanced NPK 20-20 fertilizer.
#### Cluster 1 
- Mean temperature (°C): 27.03 (Min: 20, Max: 34.83).
- Mean humidity (%): 53.81 (Min: 40.37, Max: 69.36).
- Mean moisture (%): 41.12 (Min: 20, Max: 70).
- Mean nitrogen (N): 13.32 (Min: 0, Max: 28).
- Mean potassium (K): 4.80 (Min: 0, Max: 23).
- Mean phosphorous (P): 20,57 (Min: 4, Max: 45).
- Mode soil_type: Sandy.
- Mode crop_type: Cotton.
- Mode fertilizer_name: 14-26-26.
- Analysis: This cluster has sandy soil that tends to have lower nitrogen content than Cluster 0. Potassium is quite high, while phosphorus is also quite high. Cotton plants are suited
to these conditions, with a 14-26-26 fertilizer that contains more phosphorus to support root growth.
#### Cluster 2
- Mean humidity (%): 64.48 (Min: 48.95, Max: 79.57).
- Mean moisture (%): 46.92 (Min: 20.00, Max: 70).
- Mean nitrogen (N): 12.35 (Min: 0.00, Max: 28).
- Mean potassium (K): 4.73 (Min:0.00, Max: 23).
- Mean phosphorous (P): 26.49 (Min: 4.00, Max: 46).
- Mode soil_type: Red.
- Mode crop_type: Cotton.
- Mode fertilizer_name: 14-35-14.
- Analysis: This cluster has the highest temperature compared to the others, with quite high humidity. Red soil has higher phosphorus content than Cluster 1 and is more suitable for
cotton plants. 14-35-14 fertilizer supports plant growth with high phosphorus content.

### Conclusions
Based on the analysis of the characteristics of each cluster, it can be concluded that: 
Cluster 0 is more suitable for corn cultivation on clay soil with balanced NPK fertilizer (20-20). Cluster 1 and Cluster 2 are both suitable for cotton, but the soil is different. 
Cluster 1 (Sandy soil) has lower phosphorus and uses 10-26-26 fertilizer. Cluster 2 (Red soil) has higher phosphorus and uses 14-35-14 fertilizer. The cluster with the highest 
temperature is Cluster 2, while the coldest is Cluster 1. Soil moisture is fairly uniform in all clusters, but nitrogen content is higher in Cluster 0.

### Strategy
**Cluster 0** : Can be used for farming plants with high nutrient requirements, such as green leafy vegetables or plants with fast growth cycles. <br>
**Cluster 1** : More suitable for plants that do not require a lot of additional nutrients, such as dry plants or local plants that can survive in nutrient-poor soil conditions. <br>
**Cluster 2** : Suitable for plants that require high humidity, such as rice or other tropical plants. <br>

### Featured
<p align="center">
  <img src="/Image/Image 1.png" width="400" height="250" style="display:inline-block; margin-right: 10px;">
  <img src="/Image/Image 2.png" width="400" height="250" style="display:inline-block;">
</p>
<p align="center">
  <img src="/Image/Image 3.png" width="400" height="250" style="display:inline-block; margin-right: 10px;">
  <img src="/Image/Image 4.png" width="400" height="250" style="display:inline-block;">
</p> 
<p align="center">
  <img src="/Image/Image 5.png" width="805" height="100">

### Source
Source Dataset from Kaggle : [Crop and Soil Dataset](https://www.kaggle.com/datasets/shankarpriya2913/crop-and-soil-dataset) <br>
Source Code from Colab : [Clustering](https://colab.research.google.com/drive/1t7mIf5sySn1cCVmPeX4SYKyb6ExlvhGW?usp=sharing) and [Classification](https://colab.research.google.com/drive/1h02tYin2xqtV8wQbv38oxNRTcq9AX8OH?usp=sharing)

### Remark
If you have any suggestions or feedback, please don't hesitate to contact to me in direct message on [Email](azizhabibrahim@gmail.com) and 
[LinkedIn](https://www.linkedin.com/in/mhabibr02/)




