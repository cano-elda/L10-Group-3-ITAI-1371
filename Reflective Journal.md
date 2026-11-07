Michelle's Entry:

This lab helped me understand how K-Means works without needing any labels. I kind of assumed the lowest inertia would be the best, but I learned that it just keeps going down the more clusters you add, so you have to look for the elbow instead. It was kind of cool seeing the computer find groups on its own.
I wonder how come real data doesn’t always have a clear elbow and what you’re supposed to do when the curve just keeps going down smoothly.



Xinyu's Entry:

In this lab, I learned more about unsupervised learning. More specifically, we worked with Principal Component Analysis (PCA) to reduce the number of features in a data set while keeping most of the information. Prior to this, I understood that machine learning could pick out features in data that would reveal patterns in the data, but I did not have a clear understanding of PCA.

I reduced the Iris data from four features to two features by using PCA on the data. The first feature represents about 92.46% of the variance in the original data, the second feature represents about 5.31%, and the two features together represent about 97.77% of the total variance in the data. This was a surprise to me since I expected that more than two features would be needed to represent most of the information in the original data.

As I ran PCA on the data, I also created a scatter plot of the data to better understand the results of PCA. The scatter plot really helped to make sense of the data and how PCA can make high-dimensional data easier to understand. I see that PCA does not pick existing features, but rather it makes new components from the features that currently exist. In addition, I learned that PCA is an unsupervised learning technique. This means that when running PCA on a data set, the components are calculated without the use of the class or species information.

One thing that we noticed about PCA was that high explained variance did not necessarily mean all information was kept. PCA preserves most of the data’s variation, but this does not always guarantee the best results for a classification model. It would be interesting to compare the results of a classification model before dimensionality reduction and after PCA has been applied to the data.
