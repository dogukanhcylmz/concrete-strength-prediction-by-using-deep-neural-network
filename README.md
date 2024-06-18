# concrete-strength-prediction-by-using-deep-neural-network 👾

### Requirements

**The project was developed with:**
 - jupyter notebook
 - python
 - matplotlib
 - keras
 - scikit-learn
 - pandas
 - numpy

### ✔ Purpose and Aim of This Assignment

- I have build a regression model using the deep learning keras library, and then experimented with increasing the number of training epochs and changing number of hidden layers and saw how changing these parameters impacts the performance of the model.


#### This project is the final project of the "Introduction to Deep Learning & Neural Networks with Keras" course given by IBM on Coursera. I have completed the course and here is the [link](https://www.coursera.org/account/accomplishments/verify/UGBT4XCBY4DR)

### ✔ Results and Insights
- Strength is seperated as target to build regression model since it is supervised learning
- For the Part A, it has a long tail extending towards higher MSE values. And the majority of MSE values are concentrated near 0, indicating that the model performs well on average. There are a few outliers with very high MSE values, poor performance. The distribution is skewed to the right.

- For the Part B, it is more tightly clustered compared to Part A, with a peak around 0.2. The distribution is more symmetric and narrower, it means that is more consistent model performance with fewer extreme outliers. This suggests that normalization of data may have led to a more stable model performance. It is more consistent but with higher mean MSE compared to Part A.

- For the Part C, it is similar to Part B but shifted slightly to lower MSE values. The peak is around 0.16, indicating an improvement in model performance compared to Part B. Increasing the epochs for training seems to have contributed to a better model performance.

- For the Part D, the MSE distribution for Part D shows a similar pattern to Part C but with a tighter spread. Andd the peak is around 0.17, slightly higher than Part C, but with a very narrow spread. It is consistent model performance with minimal variability. Adding more hidden layers while keeping epochs constant has resulted in stable performance.
