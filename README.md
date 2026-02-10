Assignment 2: Learning Probability Density Functions using data only

Objective:
To learn an unknown probability density function of a transformed random variable using a Generative Adversarial Network (GAN) using NO2 concentration data.

Dataset: https://www.kaggle.com/datasets/shrutibhargava94/india-air-quality-data

Methodology:
1. Data Preprocessing: Loaded dataset, extracted NO2 values, removed missing values, and normalized data.
2. Transformation: Each value x transformed using z = x + a_r*sin(b_r*x)
3. GAN Model: Generator and Discriminator neural networks designed and trained using z samples.
4. PDF Estimation: Generator used to create samples. Histogram/KDE used to estimate probability density.

Results:
![GAN PDF Graph](graph.png)

