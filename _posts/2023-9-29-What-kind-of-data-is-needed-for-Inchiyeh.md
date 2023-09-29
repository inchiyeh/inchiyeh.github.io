---
layout: post
title: What kind of data is needed for Inchiyeh?
---

In order to optimize and develop the desired model for Inchiyeh, we must find the proper dataset. So first, we need to know exactly what features the database we need has and what its structure should be. We make these features based on the performance we are considering.

![What kind of data is needed for Inchiyeh]({{ site.baseurl }}/images/posts/2023-9-29-What-kind-of-data-is-needed-for-Inchiyeh-01.png)

What we expect from Inchiyeh is that every image given to it, it will give the appropriate classes for that image. With this definition, you can understand that we are facing an image classification problem and choose the dataset accordingly. Suitable datasets for classification are datasets where the label or target of each image is clear. It means that the educational data of his class should be clear. One of the most important and famous datasets for training the image classband model is the CFAR-10 dataset.

This data set has 60 thousand images, all of which are placed in ten categories.

![What kind of data is needed for Inchiyeh]({{ site.baseurl }}/images/posts/2023-9-29-What-kind-of-data-is-needed-for-Inchiyeh-02.png)
 
This dataset is very good in terms of the number of images for the latest model, but it has a major problem, and that is the size of the images. The samples of this data set are prepared in 32 x 32 pixel sizes. Practically, the images that users will send to Inchiyeh for classification will be much larger than these images. So, the sample size of the data set we use should be larger than this. In addition, the dataset that we want should be targeted for each target by several hierarchical classes for examples. For example, when he is given a picture of a Dog, he can categorize it into Animal classes, Dogs, Short Dogs, etc. With these interpretations, it may be necessary for us to collect the appropriate dataset for our work by scraping information from different sites.
