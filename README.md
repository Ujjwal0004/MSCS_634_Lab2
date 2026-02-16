## Purpose of the Lab

The main goal of this lab is to see how K-Nearest Neighbor (KNN) and Radius Neighbor (RNN) classifier algorithms perform and are affected by their parameters. The lab uses the wine dataset provided by the sklearn library to test how the classification accuracy of KNN and RNN algorithms vary based upon different values of "k" in KNN and different values of "radius" in RNN. By doing so, it will provide insight into the importance of selecting the correct parameters when utilizing distance based machine learning models.

## Key Insights and Observations

Results of this study show that KNN has relatively stable and consistent accuracy over the range of moderately-sized values of "k." Values of "k" that are extremely small are highly sensitive to noise in the data set, and values of "k" that are excessively large significantly limit the flexibility of the model. Performance of the model tends to be best when there is a balance of the size of "k".

Accuracy of the RNN algorithm is heavily dependent on the choice of "radius". If the "radius" is too small, there may not be enough neighbors for certain samples to classify accurately. As the "radius" increases, more neighbors are included and the performance improves. However, this can lead to including irrelevant neighbors. Therefore, choosing an optimal "radius" is crucial for accurate performance of the RNN.

In general, KNN performed more consistently than RNN on the Wine data set.

## Challenges and Decisions

Managing the computing environment was one of the challenge, as I had to deal with installing libraries and working through some compatibility issues before getting things set up. Despite those challenges, I was able to train and evaluate my models using the data provided.

This lab shows that it is very important to experiment with model's parameters and understand how they will affect the results.
